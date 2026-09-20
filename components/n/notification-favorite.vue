<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/a/a7t0-2pev.css';
import '../../css/e/e4gcy2bhv.css';
import '../../css/d/ds6b51q0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a7t0-2pev"/><path class="e4gcy2bhv"/><path class="ds6b51q0d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:notification-favorite" /></template>
