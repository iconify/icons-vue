<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ce9o4-3gc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:mplx" /></template>
<style>
.ce9o4-3gc {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.89 14.913a.42.42 0 0 0 .017-.442l-4.81-8.542a.38.38 0 0 0-.328-.201H3.387c-.3 0-.485.343-.332.616L9.37 17.722a.38.38 0 0 0 .654.027zm8.728 3.36c.295 0 .48-.344.327-.611l-6.49-11.733a.38.38 0 0 0-.339-.201h-3.37c-.295 0-.48.343-.328.616l6.513 11.727a.38.38 0 0 0 .327.202zm-14.563-.726c.147.273-.039.726-.339.726H3.404c-.218 0-.404-.295-.404-.518v-4.118c0-.415.535-.568.736-.208l2.313 4.118z");
}

</style>
