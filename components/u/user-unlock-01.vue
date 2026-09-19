<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/u/ubo2nlb6e.css';
import '../../css/m/mwa5mqb6p.css';
import '../../css/y/yr2f_fpsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ubo2nlb6e"/><circle class="mwa5mqb6p"/><path class="yr2f_fpsb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:user-unlock-01" /></template>
