<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/h/hgt__cbcr.css';
import '../../css/b/bz2tnjbek.css';
import '../../css/x/xqm6y8bvi.css';
import '../../css/s/smfp-xbkt.css';
import '../../css/n/n9x4pt7yo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="hgt__cbcr"/><path class="bz2tnjbek"/><path class="xqm6y8bvi"/><path class="smfp-xbkt"/><path class="n9x4pt7yo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:water-rate" /></template>
