<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/d/dqapyabwu.css';
import '../../css/d/dos_yhbgg.css';
import '../../css/n/nrala8f6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="dqapyabwu"/><circle class="dos_yhbgg"/><path class="nrala8f6n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:music-3" /></template>
