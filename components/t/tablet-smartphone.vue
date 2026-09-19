<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/d/dp0kg2b8x.css';
import '../../css/a/a6l7ac95q.css';
import '../../css/b/bpn_39bkv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="dp0kg2b8x"/><path class="a6l7ac95q"/><path class="bpn_39bkv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:tablet-smartphone" /></template>
