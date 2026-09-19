<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/k/k52h7evjr.css';
import '../../css/u/u73h1tb4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<g class="n1lsf0bnc"><path class="k52h7evjr"/><path class="u73h1tb4c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:picture-copy" /></template>
