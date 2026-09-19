<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/j/jjl2wueme.css';
import '../../css/i/iyl1lejag.css';
import '../../css/r/r9u8fhbku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="n1lsf0bnc"><g transform="translate(2 1)"><ellipse class="jjl2wueme"/><path class="iyl1lejag"/></g><path class="r9u8fhbku"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:webcam" /></template>
