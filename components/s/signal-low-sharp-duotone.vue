<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/u/uwialcivp.css';
import '../../css/w/wf5wyrz5c.css';
import '../../css/l/lj14h_baz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="uwialcivp"/><path class="wf5wyrz5c"/><path class="lj14h_baz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:signal-low-sharp-duotone" /></template>
