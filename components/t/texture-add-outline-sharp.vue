<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s2x10mdbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:texture-add-outline-sharp" /></template>
<style>
.s2x10mdbp {
  fill: currentColor;
  d: path("M4.4 21H3v-1.4L19.6 3h1.425v1.4zM3 14.7v-2.8L11.9 3h2.8zM3 7V3h4zm18 2.3v2.8l-.475.475q-.5-.25-1.062-.387T18.3 12zM9.3 21l2.7-2.7q.05.6.188 1.163t.387 1.062L12.1 21zm7.7-2h-3v-2h3v-3h2v3h3v2h-3v3h-2z");
}

</style>
