<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/nctb2ac4r.css';
import '../../css/w/wb4xr1bwq.css';
import '../../css/y/yp_s0lbdu.css';
import '../../css/c/cds427bhl.css';
import '../../css/o/oj2ucbc0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><g class="nctb2ac4r"><path clip-rule="evenodd" class="wb4xr1bwq"/><path class="yp_s0lbdu"/></g><path clip-rule="evenodd" class="cds427bhl"/><path class="oj2ucbc0c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:stars-print" /></template>
