<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tty86b9rf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:trackpad-input-2-outline-sharp" /></template>
<style>
.tty86b9rf {
  fill: currentColor;
  d: path("M19 22h-5.425L7.6 16l1.6-1.65l2.8.825V7h2v10.825l-2.45-.7l2.575 2.575q.15.15.325.225t.375.075H19q.825 0 1.413-.587T21 18v-5h2v5q0 1.65-1.175 2.825T19 22m-4-7V6h2v9zm3 0v-4h2v4zm1 5h-4.875zM2 19V3h19v6h-2V5H4v12h1.8l1.975 2z");
}

</style>
