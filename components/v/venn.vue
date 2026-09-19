<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mx0j3m0za.css';
import '../../css/s/sevn03bfn.css';
import '../../css/m/m6j3t8g_p.css';
import '../../css/b/bmnt2jk-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="mx0j3m0za"><path class="sevn03bfn"/><path class="m6j3t8g_p"/><path class="bmnt2jk-i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:venn" /></template>
