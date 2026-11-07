<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/i/ik4yyycul.css';
import '../../css/v/v4tckp_mx.css';
import '../../css/d/dxz_62g8x.css';
import '../../css/u/uzj9wplpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ik4yyycul"/><path class="v4tckp_mx"/><path class="dxz_62g8x"/><path class="uzj9wplpi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:screencast-linear" /></template>
