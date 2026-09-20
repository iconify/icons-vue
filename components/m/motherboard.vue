<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/d/dtcuvh7uw.css';
import '../../css/c/cd3dg_wtk.css';
import '../../css/v/vv0u9-ufy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="dtcuvh7uw"/><path class="cd3dg_wtk"/><rect class="vv0u9-ufy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:motherboard" /></template>
