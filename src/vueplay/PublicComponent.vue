<template>
	<div class="p-6 bg-slate-200">
		<h2
			class="mb-12"
			style="font-weight:147"
		>
			This is a Public Component Hello World!
		</h2><input
			class="mb-6 shadow rounded p-2 w-full"
			placeholder="Type something"
			v-model="message"
		/><span style="font-weight:583">
			{{message}}
		</span><span
			class="block"
			style="color:#d92525ff"
		>
			State is preserved if only the template is updated.
		</span>
	</div>
</template>
<script>
	export default {
		data: () => ({
			message: ''
		})
	};

</script>
<style></style>