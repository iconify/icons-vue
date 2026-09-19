<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/xye_l8m-b.css';
import '../../css/r/ru8yyn5ec.css';
import '../../css/n/nrb9a_bbd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="xye_l8m-b"/><path class="ru8yyn5ec"/><path class="nrb9a_bbd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:mobile-tablet-duo" /></template>
