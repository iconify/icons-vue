<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="mq3nscf4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:sun-dim-bold" /></template>
<style>
.mq3nscf4i {
  fill: currentColor;
  d: path("M116 36v-4a12 12 0 0 1 24 0v4a12 12 0 0 1-24 0m80 92a68 68 0 1 1-68-68a68.07 68.07 0 0 1 68 68m-24 0a44 44 0 1 0-44 44a44.05 44.05 0 0 0 44-44M51.51 68.49a12 12 0 1 0 17-17l-4-4a12 12 0 0 0-17 17Zm0 119l-4 4a12 12 0 0 0 17 17l4-4a12 12 0 1 0-17-17M196 72a12 12 0 0 0 8.49-3.51l4-4a12 12 0 0 0-17-17l-4 4A12 12 0 0 0 196 72m8.49 115.51a12 12 0 0 0-17 17l4 4a12 12 0 0 0 17-17ZM48 128a12 12 0 0 0-12-12h-4a12 12 0 0 0 0 24h4a12 12 0 0 0 12-12m80 80a12 12 0 0 0-12 12v4a12 12 0 0 0 24 0v-4a12 12 0 0 0-12-12m96-92h-4a12 12 0 0 0 0 24h4a12 12 0 0 0 0-24");
}

</style>
