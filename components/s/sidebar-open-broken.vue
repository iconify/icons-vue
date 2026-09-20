<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/w/wno59xbno.css';
import '../../css/y/y3q129yby.css';
import '../../css/m/ml0cb1b5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="wno59xbno"/><path class="y3q129yby"/><path class="ml0cb1b5h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sidebar-open-broken" /></template>
