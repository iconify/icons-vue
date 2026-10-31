<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/r/rpmymt4-c.css';
import '../../css/n/n-f0l1bjt.css';
import '../../css/r/r35wb3bpv.css';
import '../../css/n/nw1asb53l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="rpmymt4-c wm-shadow"/><path class="n-f0l1bjt wm-shadow"/><path class="r35wb3bpv"/><path class="nw1asb53l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:pilcrow" /></template>
