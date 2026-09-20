<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/i/im941jbbz.css';
import '../../css/i/i-prw--3g.css';
import '../../css/c/c1788rp0v.css';
import '../../css/t/t0r8m-b4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="im941jbbz"/><path class="i-prw--3g"/><path class="c1788rp0v"/><path class="t0r8m-b4e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:smart-home-broken" /></template>
