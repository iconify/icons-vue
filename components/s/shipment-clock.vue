<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/f/f3mi_ybsx.css';
import '../../css/i/iq4poybgc.css';
import '../../css/v/vlq40abrs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f3mi_ybsx"/><path class="iq4poybgc"/><path class="vlq40abrs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:shipment-clock" /></template>
