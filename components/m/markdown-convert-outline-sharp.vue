<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s929sd3rz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:markdown-convert-outline-sharp" /></template>
<style>
.s929sd3rz {
  fill: currentColor;
  d: path("M4 18V6v2.28v-.857zm1.808-3.308h.884v-4.5h1.616v3h.884v-3h1.616v4.5h.884V9.308H5.808zM3 19V5h18v3.97q-.233-.195-.473-.365T20 8.28V6H4v12h9.692v1zm18 0h-4.538v-4.538h1v2.77q1.117-.236 1.842-1.126t.725-2.046q0-1.364-.947-2.308t-2.303-.944v-1q1.767 0 3.009 1.236q1.24 1.235 1.24 2.995q0 1.357-.765 2.43q-.767 1.072-1.967 1.531H21z");
}

</style>
