<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dwkm_4bhp.css';
import '../../css/c/cnzm0bbzs.css';
import '../../css/n/nh7t5gkgv.css';
import '../../css/o/oqke668hh.css';
import '../../css/k/kouamewrq.css';
import '../../css/q/q7csmybvi.css';
import '../../css/k/k-fwjfxbb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dwkm_4bhp"/><path class="cnzm0bbzs"/><path class="nh7t5gkgv"/><path class="oqke668hh"/><path class="kouamewrq"/><path class="q7csmybvi"/><path class="k-fwjfxbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:sportsmedal" /></template>
