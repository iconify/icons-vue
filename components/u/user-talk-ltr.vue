<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t8_m0n41d.css';
import '../../css/h/h7o1n1z4d.css';
import '../../css/k/k79q3xboj.css';
import '../../css/r/r5d2n_xgw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="t8_m0n41d"/><path class="h7o1n1z4d"/><circle class="k79q3xboj"/><circle class="r5d2n_xgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:user-talk-ltr" /></template>
