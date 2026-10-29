<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/n/nx0cbsb0t.css';
import '../../css/d/d3344bbeg.css';
import '../../css/l/l3uhytb6s.css';
import '../../css/g/gr51g0biu.css';
import '../../css/n/n52ulu9ns.css';
import '../../css/c/c6mo7m0bg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="nx0cbsb0t wm-deco"/><path class="d3344bbeg wm-deco"/><path class="l3uhytb6s wm-deco"/><path class="gr51g0biu wm-k"/><path class="n52ulu9ns wm-s"/><path class="c6mo7m0bg wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:user-clock-blueprint" /></template>
