<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/g/g3zz7abxt.css';
import '../../css/i/imnbyubve.css';
import '../../css/e/e9gx80b9k.css';
import '../../css/n/nlc85z_0n.css';
import '../../css/u/ujw1uw9ao.css';
import '../../css/r/rhc-hyb4w.css';
import '../../css/e/eerdr7h-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="g3zz7abxt wm-k"/><path class="imnbyubve wm-a"/><path class="e9gx80b9k wm-shadow"/><path class="nlc85z_0n wm-k"/><path class="ujw1uw9ao wm-k"/><path class="rhc-hyb4w wm-a"/><path class="eerdr7h-p wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:network-engrave" /></template>
