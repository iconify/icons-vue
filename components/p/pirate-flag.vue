<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mgniksc_l.css';
import '../../css/o/obin-pbyc.css';
import '../../css/w/wl2vi-wfs.css';
import '../../css/v/vr6050b8a.css';
import '../../css/e/e7siu6r3e.css';
import '../../css/q/qsam29but.css';
import '../../css/u/u2r7j-bxu.css';
import '../../css/r/re66l4b7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path clip-rule="evenodd" class="mgniksc_l"/><path class="obin-pbyc"/><path class="wl2vi-wfs"/><path class="vr6050b8a"/><path clip-rule="evenodd" class="e7siu6r3e"/><path class="qsam29but"/><path class="u2r7j-bxu"/><path class="re66l4b7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:pirate-flag" /></template>
