<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/q/qi30vz44o.css';
import '../../css/e/ehgxs22fz.css';
import '../../css/h/hq7o26lao.css';
import '../../css/o/o1x490v7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="qi30vz44o"/><path class="ehgxs22fz"/><path class="hq7o26lao"/><path class="o1x490v7y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:palette-broken" /></template>
