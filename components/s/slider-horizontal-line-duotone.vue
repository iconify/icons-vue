<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/t/tke-0za-g.css';
import '../../css/n/ndk6zfbbq.css';
import '../../css/t/tiuqf-byk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="tke-0za-g"/><path class="ndk6zfbbq"/><path class="tiuqf-byk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:slider-horizontal-line-duotone" /></template>
