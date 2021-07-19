<template>
	<div class="resp">
        	<PictureHigh />
		<Navbar />
		<main>
		<nuxt />
		</main>
		<Footer />
	</div>
</template>
// すべての共通して使うコンポーネントはこのファイルを介して作動する starting components this file.
<script>
	import PictureHigh from "/components/PictureHigh";
	import Navbar from "/components/Navbar"; // headerをインポート
	import Footer from "/components/Footer"; // footerをインポート

	export default {
		components: {
            		PictureHigh,
			Navbar,
			Footer,
		}
	};
</script>
