<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w7nt6eb_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:text-select-move-forward-word-outline-sharp" /></template>
<style>
.w7nt6eb_j {
  fill: currentColor;
  d: path("m16.712 15.289l-.708-.689l2.075-2.1H11v-1h7.079l-2.075-2.1l.707-.688L20 12zM5 19h2.923V5H5zm-1 1V4h4.923v16zm7.385 0v-1.23h1.23V20zm0-14.77V4h1.23v1.23zM15.077 20v-1.23h1.23V20zm0-14.77V4h1.23v1.23zM18.769 20v-1.23H20V20zm0-14.77V4H20v1.23zM5 19h2.923z");
}

</style>
