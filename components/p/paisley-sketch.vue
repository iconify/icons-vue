<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/y/yd-40xbpd.css';
import '../../css/g/gt4wshb-r.css';
import '../../css/b/bmi4u2bke.css';
import '../../css/l/lz3_99bxh.css';
import '../../css/r/rg78pebrd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wm-k yd-40xbpd"/><path class="gt4wshb-r wm-a"/><path class="bmi4u2bke wm-k"/><path class="lz3_99bxh wm-a"/><path class="rg78pebrd wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:paisley-sketch" /></template>
