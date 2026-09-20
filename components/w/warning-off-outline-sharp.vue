<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j3k17mbbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:warning-off-outline-sharp" /></template>
<style>
.j3k17mbbq {
  fill: currentColor;
  d: path("M11.566 17.434q-.182-.182-.182-.434t.182-.434t.434-.181t.434.181t.182.434t-.182.434t-.434.181t-.434-.181m-.066-2.05v-3.89l1 1v2.89zm7.614.893l-2.72-2.714L12 6l-1.175 2l-.72-.72L12 4zM4.45 19h13.129l-8.31-8.31zm15.833 2.704L18.579 20H2.73L8.55 9.971L2.271 3.692l.714-.713L20.996 20.99zm-6.664-10.91");
}

</style>
