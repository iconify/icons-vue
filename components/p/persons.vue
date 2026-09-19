<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/b/bfdztm4yf.css';
import '../../css/f/f5j14_hcn.css';
import '../../css/l/lo_jtt6tv.css';
import '../../css/z/zu93z5r4w.css';
import '../../css/l/lw57arbmp.css';
import '../../css/a/aym7j7bua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="bfdztm4yf"/><path class="f5j14_hcn"/><path class="lo_jtt6tv"/><path class="zu93z5r4w"/><path class="lw57arbmp"/><path class="aym7j7bua"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:persons" /></template>
