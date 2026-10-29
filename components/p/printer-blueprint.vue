<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/u/uvwyxkbmx.css';
import '../../css/y/y40g73z9t.css';
import '../../css/o/o7-ag87sb.css';
import '../../css/c/ce4_fwbku.css';
import '../../css/e/eefh2vbou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="uvwyxkbmx wm-deco"/><path class="wm-deco y40g73z9t"/><path class="o7-ag87sb wm-deco"/><path class="ce4_fwbku wm-k"/><path class="eefh2vbou wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:printer-blueprint" /></template>
