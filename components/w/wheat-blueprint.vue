<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/z/z5xnrgtsv.css';
import '../../css/g/gcwkl5bcj.css';
import '../../css/q/q2afrlb6o.css';
import '../../css/k/kjgpvobgb.css';
import '../../css/h/h0tj1xbrb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="wm-deco z5xnrgtsv"/><path class="gcwkl5bcj wm-deco"/><path class="q2afrlb6o wm-deco"/><path class="kjgpvobgb"/><path class="h0tj1xbrb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:wheat-blueprint" /></template>
