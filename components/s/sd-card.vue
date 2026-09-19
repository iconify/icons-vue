<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/j/jt0xnq6sh.css';
import '../../css/k/k907rib4j.css';
import '../../css/a/a4jy-o8-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="jt0xnq6sh"/><path class="k907rib4j"/><path class="a4jy-o8-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:sd-card" /></template>
