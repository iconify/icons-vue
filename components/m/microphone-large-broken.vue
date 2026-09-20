<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/o/ow44-uqiu.css';
import '../../css/f/fvun-abzf.css';
import '../../css/c/c_apmbcjm.css';
import '../../css/d/df2pzh_wy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ow44-uqiu"/><path class="fvun-abzf"/><path class="c_apmbcjm"/><path class="df2pzh_wy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:microphone-large-broken" /></template>
