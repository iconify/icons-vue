<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ool-q2r1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:texture-minus-outline-sharp" /></template>
<style>
.ool-q2r1o {
  fill: currentColor;
  d: path("M4.708 20H4v-.708L19.292 4h.714v.708zm5.765 0l1.143-1.142V20zM14 17.616v-1h7v1zM4 13.527v-1.415L12.111 4h1.416zm12.242.704L20 10.473v1.416l-2.342 2.342zM4 6.346V4h2.346z");
}

</style>
