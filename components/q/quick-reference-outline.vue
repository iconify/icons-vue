<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yb7v0jb7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:quick-reference-outline" /></template>
<style>
.yb7v0jb7v {
  fill: currentColor;
  d: path("M15.923 19h.77v-3h-.77zm.385-3.827q.161.02.273-.102q.111-.121.111-.283t-.12-.273t-.264-.111q-.162 0-.274.111q-.111.112-.111.273q0 .143.111.264q.112.121.274.121M5 4v6.366v-.058V20zv4zm2.5 9.5h3.271q.16-.267.34-.517t.38-.483H7.5zm0 4h2.46q-.037-.25-.037-.49t.017-.51H7.5zM5.616 21q-.691 0-1.153-.462T4 19.385V4.615q0-.69.463-1.152T5.616 3H13.5L18 7.5v3.05q-.263-.073-.504-.12q-.24-.045-.496-.064V8h-4V4H5.616q-.231 0-.424.192T5 4.615v14.77q0 .23.192.423t.423.192h5.233q.16.287.34.537t.399.463zm13.527-7.143q1.165 1.164 1.165 2.835t-1.165 2.836t-2.835 1.164t-2.836-1.164t-1.164-2.836q0-1.67 1.164-2.835q1.165-1.165 2.836-1.165t2.835 1.165");
}

</style>
