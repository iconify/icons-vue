<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt_l_wkmq.css';
import '../../css/s/s_rh6-bjn.css';
import '../../css/r/rfmo84bve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dt_l_wkmq"/><path class="s_rh6-bjn"/><path class="rfmo84bve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:stockchart" /></template>
