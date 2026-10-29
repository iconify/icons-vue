<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/r/r6229ru9h.css';
import '../../css/q/qiq8lcr5c.css';
import '../../css/d/dhmyu5bqg.css';
import '../../css/y/yfxqptq_n.css';
import '../../css/m/mnio4ybyx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="r6229ru9h"/><path class="qiq8lcr5c wm-k"/><path class="dhmyu5bqg wm-k"/><path class="wm-a yfxqptq_n"/><path class="mnio4ybyx wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:marigold-sketch" /></template>
