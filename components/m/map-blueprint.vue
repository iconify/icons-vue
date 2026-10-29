<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/p/p_dvz6bea.css';
import '../../css/n/nge5cfbll.css';
import '../../css/w/w1vuqf11k.css';
import '../../css/k/knuz6bbww.css';
import '../../css/l/lt61czblz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="p_dvz6bea wm-deco"/><path class="nge5cfbll wm-deco"/><path class="w1vuqf11k wm-k"/><path class="knuz6bbww wm-a"/><path class="lt61czblz wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:map-blueprint" /></template>
