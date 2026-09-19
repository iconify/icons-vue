<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g_oe7b2wk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-fiber-pin" /></template>
<style>
.g_oe7b2wk {
  fill: currentColor;
  d: path("M5.5 10.5h2v1h-2zM22 4H2v16h20zM9 13H5.5v2H4V9h5zm3.5 2H11V9h1.5zm7.5 0h-1.2l-2.55-3.5V15H15V9h1.25l2.5 3.5V9H20z");
}

</style>
