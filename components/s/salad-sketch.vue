<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/k/k4a-eqbya.css';
import '../../css/l/lf1y4ul7m.css';
import '../../css/u/uc0p6lh_l.css';
import '../../css/x/xp8ee6bcq.css';
import '../../css/u/uikupyynh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="k4a-eqbya wm-deco"/><path class="lf1y4ul7m wm-k"/><path class="uc0p6lh_l wm-k"/><path class="wm-a xp8ee6bcq"/><path class="uikupyynh wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:salad-sketch" /></template>
