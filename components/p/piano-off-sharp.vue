<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uzr9v6bnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:piano-off-sharp" /></template>
<style>
.uzr9v6bnx {
  fill: currentColor;
  d: path("M19.833 21.26L18.573 20H4V5.427l-1.26-1.26l.714-.713l17.092 17.092zM20 17.188l-1-1V5h-2.404v8.785L13.212 10.4V5h-2.423v2.977L6.812 4H20zM5 19h3.654v-4.808h-1.25V8.831L5 6.427zm4.539 0h4.922v-3.111l-3.684-3.685l.115 1.988H9.54zm5.807 0h2.227l-2.227-2.227z");
}

</style>
