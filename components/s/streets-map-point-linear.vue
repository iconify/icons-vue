<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/x/xvjk-cbox.css';
import '../../css/i/ijmauiszs.css';
import '../../css/m/mdco-nbti.css';
import '../../css/z/zwiw2-bkv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="xvjk-cbox"/><path class="ijmauiszs"/><path class="mdco-nbti"/><path class="zwiw2-bkv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:streets-map-point-linear" /></template>
