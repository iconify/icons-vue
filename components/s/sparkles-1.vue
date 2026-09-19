<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ctmlb8_7m.css';
import '../../css/c/cd00vabay.css';
import '../../css/h/hl1t43cng.css';
import '../../css/i/i6p_zx0xf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ctmlb8_7m"><path class="cd00vabay"/><path class="hl1t43cng"/><path class="i6p_zx0xf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:sparkles-1" /></template>
