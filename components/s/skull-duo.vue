<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/zvjmf6bdk.css';
import '../../css/r/r324r-ddk.css';
import '../../css/h/hk8-dea2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="zvjmf6bdk"/><path class="r324r-ddk"/><path class="hk8-dea2h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:skull-duo" /></template>
