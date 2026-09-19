<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/qbgb-f08m.css';
import '../../css/t/tk6_7_b3w.css';
import '../../css/s/s2cet7bec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="qbgb-f08m"/><path clip-rule="evenodd" class="tk6_7_b3w"/><path class="s2cet7bec"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:pen-fountain-duo" /></template>
