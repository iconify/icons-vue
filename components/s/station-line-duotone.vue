<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/a/aq9vwpvuv.css';
import '../../css/m/mml9srb2o.css';
import '../../css/u/um_27sbup.css';
import '../../css/j/jnepjhbrg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="aq9vwpvuv"/><path class="mml9srb2o"/><circle class="um_27sbup"/><path class="jnepjhbrg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:station-line-duotone" /></template>
