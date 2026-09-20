<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l-9s1pbiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:quick-reference-outline-sharp" /></template>
<style>
.l-9s1pbiv {
  fill: currentColor;
  d: path("M15.923 19h.77v-3h-.77zm.385-3.827q.161.02.273-.102q.111-.121.111-.283t-.12-.273t-.264-.111q-.162 0-.274.111q-.111.112-.111.273q0 .143.111.264q.112.121.274.121M5 4v6.366v-.058V20zv4zm2.5 9.5h3.29q.16-.287.34-.527t.38-.473H7.5zm0 4h2.479q-.037-.25-.046-.5t.008-.5H7.5zM4 21V3h9.5L18 7.5v3.03q-.244-.072-.484-.109q-.241-.036-.516-.055V8h-4V4H5v16h5.848q.16.287.349.527q.19.24.409.473zm15.143-7.143q1.165 1.164 1.165 2.835t-1.165 2.836t-2.835 1.164t-2.836-1.164t-1.164-2.836q0-1.67 1.164-2.835q1.165-1.165 2.836-1.165t2.835 1.165");
}

</style>
