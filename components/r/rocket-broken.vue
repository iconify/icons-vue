<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/r/r75ibw1at.css';
import '../../css/y/ywaaisbty.css';
import '../../css/q/qevjdebni.css';
import '../../css/t/tangbccak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="r75ibw1at"/><path class="ywaaisbty"/><path class="qevjdebni"/><path class="tangbccak"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rocket-broken" /></template>
