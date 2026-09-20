<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ghvfd6btu.css';
import '../../css/v/vio9gfbpv.css';
import '../../css/g/gu24prbpy.css';
import '../../css/l/lsudu1uhs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="ghvfd6btu"/><path class="vio9gfbpv"/><path class="gu24prbpy"/><path class="lsudu1uhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:wine-glass" /></template>
