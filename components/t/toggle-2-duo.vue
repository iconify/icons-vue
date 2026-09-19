<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/nb23tyfhv.css';
import '../../css/y/ywir2hbst.css';
import '../../css/k/k2kfsbcgf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="nb23tyfhv"/><path class="ywir2hbst"/><path class="k2kfsbcgf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:toggle-2-duo" /></template>
