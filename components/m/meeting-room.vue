<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/u/u-3e0irwq.css';
import '../../css/u/ub1f79cjh.css';
import '../../css/r/r6wfj1bre.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="u-3e0irwq"/><path class="ub1f79cjh"/><path class="r6wfj1bre"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:meeting-room" /></template>
