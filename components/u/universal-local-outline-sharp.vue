<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xfz-79w3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:universal-local-outline-sharp" /></template>
<style>
.xfz-79w3n {
  fill: currentColor;
  d: path("M4 18h16V6H4zm-1 1V5h18v14zm1-1V6zm7.422-6.233q-.23-.233-.23-.578t.234-.575t.577-.23t.575.234t.23.578t-.233.574t-.578.23t-.575-.233M12 16.039q1.621-1.38 2.426-2.573t.805-2.193q0-1.529-.972-2.42q-.972-.892-2.259-.892t-2.259.892t-.972 2.42q0 1 .805 2.193T12 16.04");
}

</style>
