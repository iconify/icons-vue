<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/y/ycpt8bb8i.css';
import '../../css/y/yhit5qlfz.css';
import '../../css/v/vv41l5bpa.css';
import '../../css/d/d6zxgccaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#healthiconsSodiumFreeNegative0)" class="cuyn6tgcc"><path clip-rule="evenodd" class="ycpt8bb8i"/><path class="yhit5qlfz"/><path clip-rule="evenodd" class="vv41l5bpa"/></g><defs><clipPath id="healthiconsSodiumFreeNegative0"><path class="d6zxgccaz"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:sodium-free-negative" /></template>
