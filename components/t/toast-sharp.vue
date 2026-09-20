<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wv6jnluww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:toast-sharp" /></template>
<style>
.wv6jnluww {
  fill: currentColor;
  d: path("M6.5 17.5h11v-1h-11zM4 20V4h16v16z");
}

</style>
