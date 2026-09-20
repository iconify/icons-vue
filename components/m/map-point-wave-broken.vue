<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/c/c8_7p-sow.css';
import '../../css/v/vv52kbcqz.css';
import '../../css/m/mma4vmbcv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="c8_7p-sow"/><path class="vv52kbcqz"/><path class="mma4vmbcv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:map-point-wave-broken" /></template>
