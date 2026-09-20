<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/i/i6sjuzl3m.css';
import '../../css/t/t2cylssnp.css';
import '../../css/i/i1h42obmq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="i6sjuzl3m"/><path class="t2cylssnp"/><path class="i1h42obmq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:panorama-broken" /></template>
