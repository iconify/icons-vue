<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/p/pc5ui8bts.css';
import '../../css/t/t-1pbabqs.css';
import '../../css/d/du7h3-swe.css';
import '../../css/y/yvgsujbae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="pc5ui8bts wm-k"/><path class="t-1pbabqs wm-k"/><path class="du7h3-swe wm-a"/><path class="wm-a yvgsujbae"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:x-circle-sketch" /></template>
