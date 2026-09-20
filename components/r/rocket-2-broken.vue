<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/q/q31ynxbic.css';
import '../../css/g/gm04g_b8c.css';
import '../../css/d/ds2ci9blu.css';
import '../../css/x/xpn4xccyr.css';
import '../../css/t/t4euwlpjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="q31ynxbic"/><path class="gm04g_b8c"/><path class="ds2ci9blu"/><path class="xpn4xccyr"/><path class="t4euwlpjt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rocket-2-broken" /></template>
