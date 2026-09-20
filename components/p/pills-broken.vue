<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/h/hrkp-tbak.css';
import '../../css/v/vr39ulzpl.css';
import '../../css/h/h0g48wbnz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="hrkp-tbak"/><path class="vr39ulzpl"/><path class="h0g48wbnz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:pills-broken" /></template>
