<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/bg3webbfv.css';
import '../../css/l/l8s_-sofp.css';
import '../../css/n/n26hyfvem.css';
import '../../css/d/dvk4vob1f.css';
import '../../css/a/a6-otcbrn.css';
import '../../css/n/nrmru6bot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="bg3webbfv"/><path class="l8s_-sofp"/><path class="n26hyfvem"/><path class="dvk4vob1f"/><path class="a6-otcbrn"/><path class="nrmru6bot"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:sunrise-over-mountains" /></template>
