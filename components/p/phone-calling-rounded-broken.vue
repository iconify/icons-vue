<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/b/bucfw6bdg.css';
import '../../css/q/qy44fxbnk.css';
import '../../css/q/qatxeebvq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="bucfw6bdg"/><path class="qy44fxbnk"/><path class="qatxeebvq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:phone-calling-rounded-broken" /></template>
