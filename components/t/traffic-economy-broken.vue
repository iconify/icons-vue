<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/g/g9i31fsft.css';
import '../../css/d/d992vwbtc.css';
import '../../css/i/izwsa0kiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="g9i31fsft"/><path class="d992vwbtc"/><path class="izwsa0kiq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:traffic-economy-broken" /></template>
