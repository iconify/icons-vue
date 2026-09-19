<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/lafhkbbho.css';
import '../../css/e/etbgu2b1p.css';
import '../../css/w/w4vxnac6h.css';
import '../../css/d/d6d0w5b6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="lafhkbbho"/><path class="etbgu2b1p"/><path class="w4vxnac6h"/><path class="d6d0w5b6c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:play-circle-duo" /></template>
