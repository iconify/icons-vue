<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/t83iogb4n.css';
import '../../css/p/p63pfdb4g.css';
import '../../css/e/ef2rn-54p.css';
import '../../css/c/cl4k-1bjk.css';
import '../../css/h/h5c6-vbwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="t83iogb4n wm-k"/><path class="p63pfdb4g wm-k"/><path class="ef2rn-54p wm-k"/><path class="cl4k-1bjk wm-shine"/><path class="h5c6-vbwk wm-deco"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-anime:moon" /></template>
