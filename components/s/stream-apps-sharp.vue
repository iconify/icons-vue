<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n2hbcv4kg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:stream-apps-sharp" /></template>
<style>
.n2hbcv4kg {
  fill: currentColor;
  d: path("M14 17V8h9v7h-7zm-9 6V1h14v6h-2V6H7v12h10v-1h2v6z");
}

</style>
