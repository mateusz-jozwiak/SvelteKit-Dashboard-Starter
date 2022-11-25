<script>
	import Nav from '$lib/nav.svelte';
	import SideBar from '$lib/sidebar.svelte';
	import "../app.css";
	import Sidebar from '../lib/sidebar.svelte';
</script>



  





















<div class="drawer drawer-mobile">
	<input id="my-drawer-2" type="checkbox" class="drawer-toggle" />
	<div class="drawer-content flex flex-col items-center bg-neutral">
		


<div class="navbar bg-base-200 mx-auto p-0 sticky top-0 z-30 w-full px-2 py-4 sm:px-4 shadow-xl">
	<div class="flex-none">
		
		<label for="my-drawer-2" class="btn lg:hidden"><svg class="h-8 w-8 text-white"  width="24" height="24" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round">  <path stroke="none" d="M0 0h24v24H0z"/>  <line x1="4" y1="6" x2="20" y2="6" />  <line x1="4" y1="12" x2="20" y2="12" />  <line x1="4" y1="18" x2="20" y2="18" /></svg>
			</label>
	  
	</div>
	<div class="flex-1 m-0 p-0">
	  <a class="btn btn-ghost normal-case text-xl">alkoCALC</a>
	</div>
	
	<button class="btn btn-square btn-ghost">
		<svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" class="inline-block w-5 h-5 stroke-current"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 12h.01M12 12h.01M19 12h.01M6 12a1 1 0 11-2 0 1 1 0 012 0zm7 0a1 1 0 11-2 0 1 1 0 012 0zm7 0a1 1 0 11-2 0 1 1 0 012 0z"></path></svg>
	  </button>
  </div>


	  <slot></slot>
	  
	
	</div> 


	
	<div class="drawer-side">
	  <label for="my-drawer-2" class="drawer-overlay"></label> 
	  <ul class="menu p-4 w-80 bg-base-100 text-base-content m-0 p-0">
		
		<div class="navbar bg-base-200 m-0 pl-02">
			
			

			<div class="flex-none">
		
				<label for="my-drawer-2" class="btn lg:hidden "><svg class=" h-8 w-8 text-white"  width="24" height="24" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round">  <path stroke="none" d="M0 0h24v24H0z"/>  <line x1="4" y1="6" x2="20" y2="6" />  <line x1="4" y1="12" x2="20" y2="12" />  <line x1="4" y1="18" x2="20" y2="18" /></svg>
					</label>
			  
			</div>
			<a class="btn btn-ghost normal-case text-xl">alkoCalc</a>

	


		  </div>

		  

		  <ul class="menu bg-base-100 p-2">
			<li class="menu-title">
			  <span>Category</span>
			</li>
			<li><a href="/">Home</a></li>
			<li><a href="/about">About</a></li>
			<li class="menu-title">
			  <span>Category</span>
			</li>
			<li><a href="/settings">Settings</a></li>
			<li><a href="/settings/profile">Profile</a></li>
		  </ul>

	  </ul>
	
	</div>
  </div>



