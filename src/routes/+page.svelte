<script>
	import SmallTask from '$lib/SmallTask.svelte';
	import Title from '$lib/Title.svelte';
</script>



<div class="flex flex-col items-center">
	<nav class="flex bg-gray-100 p-3 w-full shadow-lg mb-5 justify-center">
		<div class="flex w-2/3">
		<h1 class="">My App</h1>
		<div class="flex ml-auto gap-4">
			<button class="p-1 w-16 hover:bg-gray-400 rounded-lg duration-300">Home</button>
			<button class="p-1 w-16  hover:bg-gray-400 rounded-lg">Login</button>
		</div>
		</div>
	</nav>


<div class="flex flex-col w-1/3 p-4  ">


	<form class="flex flex-col p-4 my-1 gap-4 bg-gray-200 rounded-lg ">
		<label>Put your task that want tobe analyze...
			<textarea class="bg-gray-300 shadow-lg rounded-lg p-1 border-gray-400 border h-24 w-full"></textarea>
		</label>
		<button class="bg-gray-500 rounded-lg shadow-lg p-1"> Help Me </button>
	</form>


	<div class="bg-gray-300 p-2 rounded-xl">
		<Title title_name="Problems" />
		<p class="py-2 ">This is my problem and these are the steps to finish it This is my problem and these are the steps to finish it This is my problem and these are the steps to finish it </p>
	</div>

	<div class="bg-gray-300 p-2 my-5 rounded-xl">



	<div class="my-3">
		<Title title_name="Prepare" />
		<div>
			<SmallTask task_name="learn something new"/>
			<SmallTask task_name="Ask a friends" />
		</div>
	</div>


		<div class="my-3">
			<Title title_name="Do It" />
			<div>
				<SmallTask task_name="Do properly"/>
				<SmallTask task_name="Dont Cheat" />
			</div>
		</div>


		<div class="my-3">
		<Title title_name="Evaluate" />
		<div>
			<SmallTask task_name="Check answers"/>
			<SmallTask task_name="Review the wrong one" />
		</div>
	</div>

	</div>
</div>


</div>