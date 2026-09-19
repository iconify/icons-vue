<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-ulsw_ta.css';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/dtjq5ubdn.css';
import '../../css/p/p6udk3bpf.css';
import '../../css/j/jz4o31b3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><path id="SVG7uvgHdPV" class="m-ulsw_ta"/></defs><g class="ft5dv1b6b"><use href="#SVG7uvgHdPV"/><path class="dtjq5ubdn"/><path class="p6udk3bpf"/><use href="#SVG7uvgHdPV"/><path class="jz4o31b3z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:shamrock" /></template>
