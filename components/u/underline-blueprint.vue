<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/l/lbkshfbwn.css';
import '../../css/e/eb2qabupy.css';
import '../../css/a/axkxll7ka.css';
import '../../css/e/ey8whr8xr.css';
import '../../css/r/r5dk_vx7g.css';
import '../../css/x/xlsaqmbjh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="lbkshfbwn wm-deco"/><path class="eb2qabupy wm-deco"/><path class="axkxll7ka wm-k"/><path class="ey8whr8xr wm-a"/><path class="r5dk_vx7g wm-k"/><path class="wm-a xlsaqmbjh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:underline-blueprint" /></template>
