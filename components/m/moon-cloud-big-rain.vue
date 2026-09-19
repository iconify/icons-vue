<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/n/nrka6qbcl.css';
import '../../css/c/clkta5wrk.css';
import '../../css/h/hagc2nfwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="nrka6qbcl"/><path class="clkta5wrk"/><path class="hagc2nfwh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:moon-cloud-big-rain" /></template>
