<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e2-7umr8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:stylus-pen-outline-sharp" /></template>
<style>
.e2-7umr8l {
  fill: currentColor;
  d: path("m6.885 15.308l2.134-8.174h1.539V5.788L11.788 3h.424l1.25 2.789v1.346H15l2.135 8.173zm1.317-1h7.615l-1.592-6.173h-4.45zM5 20l.827-2.308h12.346L19 20zm3.202-5.692h7.615z");
}

</style>
