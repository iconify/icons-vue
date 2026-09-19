<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/l/lq73idbwi.css';
import '../../css/w/wlbr5cbsv.css';
import '../../css/u/uj-9c3b5e.css';
import '../../css/u/ucxvrob9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="lq73idbwi"/><path class="wlbr5cbsv"/><path class="uj-9c3b5e"/><path class="ucxvrob9l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:quran-02" /></template>
