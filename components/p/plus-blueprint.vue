<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/m/mxzs_g6co.css';
import '../../css/b/bd7s4lb_v.css';
import '../../css/n/nh6kcmtjb.css';
import '../../css/t/tv0sudbup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="mxzs_g6co wm-deco"/><path class="bd7s4lb_v wm-deco"/><path class="nh6kcmtjb"/><path class="tv0sudbup"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:plus-blueprint" /></template>
