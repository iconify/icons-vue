<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rtslvjbon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-local-drink" /></template>
<style>
.rtslvjbon {
  fill: currentColor;
  d: path("m3 2l2.21 20H18.8L21 2zm9 17c-1.66 0-3-1.34-3-3c0-2 3-5.4 3-5.4s3 3.4 3 5.4c0 1.66-1.34 3-3 3m6.33-11H5.67l-.44-4h13.53z");
}

</style>
