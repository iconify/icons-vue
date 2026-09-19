<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/k091tb0hb.css';
import '../../css/q/qkp19wbeb.css';
import '../../css/b/b-f3-gzch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><rect class="k091tb0hb"/><path class="qkp19wbeb"/><rect class="b-f3-gzch"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:mobile-tablet" /></template>
