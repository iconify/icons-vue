<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/n/nrka6qbcl.css';
import '../../css/c/clkta5wrk.css';
import '../../css/c/cns1e8f3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="nrka6qbcl"/><path class="clkta5wrk"/><path class="cns1e8f3x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:sun-cloud-big-rain-02" /></template>
