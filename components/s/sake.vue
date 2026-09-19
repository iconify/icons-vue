<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/bmd_8-byf.css';
import '../../css/c/crte8sbou.css';
import '../../css/y/yd-unbbsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="bmd_8-byf"/><path class="crte8sbou"/><path class="yd-unbbsc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:sake" /></template>
