<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/j/jeest4e1g.css';
import '../../css/d/dcs8ey39w.css';
import '../../css/h/hx-wuc0xm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="jeest4e1g"/><path class="dcs8ey39w"/><path class="hx-wuc0xm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:printer-minimalistic-linear" /></template>
