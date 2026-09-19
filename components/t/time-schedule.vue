<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/h/h9vgzhszr.css';
import '../../css/q/qi7u9v67a.css';
import '../../css/f/fi254ke4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="h9vgzhszr"/><path class="qi7u9v67a"/><path class="fi254ke4d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:time-schedule" /></template>
