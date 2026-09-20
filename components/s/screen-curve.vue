<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/rg-n6qb2c.css';
import '../../css/s/sgvz6u9ad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<g class="ft5dv1b6b"><path class="rg-n6qb2c"/><path class="sgvz6u9ad"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex-color:screen-curve" /></template>
