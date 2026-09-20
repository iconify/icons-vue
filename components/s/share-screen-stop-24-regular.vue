<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ngm-lx3kw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:share-screen-stop-24-regular" /></template>
<style>
.ngm-lx3kw {
  fill: currentColor;
  d: path("M2 6.25A2.25 2.25 0 0 1 4.25 4h15.5A2.25 2.25 0 0 1 22 6.25v11.5A2.25 2.25 0 0 1 19.75 20H4.25A2.25 2.25 0 0 1 2 17.75zm2.25-.75a.75.75 0 0 0-.75.75v11.5c0 .414.336.75.75.75h15.5a.75.75 0 0 0 .75-.75V6.25a.75.75 0 0 0-.75-.75zm3.97 2.715a.75.75 0 0 1 1.06 0l2.72 2.72l2.725-2.716a.75.75 0 0 1 1.06 1.062l-2.724 2.715l2.724 2.724a.75.75 0 1 1-1.06 1.06L12 13.057L9.28 15.78a.75.75 0 1 1-1.06-1.06l2.72-2.724l-2.72-2.72a.75.75 0 0 1 0-1.06");
}

</style>
