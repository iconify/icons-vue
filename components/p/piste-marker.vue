<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yb25s6bym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:piste-marker" /></template>
<style>
.yb25s6bym {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.125 1.75h7.75q3.375 0 3.375 3.375v4.75q0 3.375-3.375 3.375H12.75v4.553q.65.162.989.83q.45.882-.132 1.683q-.595.819-1.607.819t-1.607-.819q-.582-.801-.132-1.683q.339-.668.989-.831V13.25H8.125q-3.375 0-3.375-3.375v-4.75q0-3.375 3.375-3.375");
}

</style>
