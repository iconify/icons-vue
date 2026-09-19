<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ro5624blo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-table-restaurant" /></template>
<style>
.ro5624blo {
  fill: currentColor;
  d: path("m22.33 11l-2-7H3.67l-2 7H5.2L4 20h2l.67-5h10.67l.66 5h2l-1.2-9zm-15.4 2l.27-2h9.6l.27 2z");
}

</style>
