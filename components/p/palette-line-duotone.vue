<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/i/idco1xbej.css';
import '../../css/r/rifo2czrt.css';
import '../../css/h/hq7o26lao.css';
import '../../css/m/mlq66nbgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="idco1xbej"/><path class="rifo2czrt"/><path class="hq7o26lao"/><path class="mlq66nbgo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:palette-line-duotone" /></template>
