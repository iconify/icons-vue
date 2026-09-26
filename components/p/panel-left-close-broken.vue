<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/q/q_3h0ub-d.css';
import '../../css/m/ml0cb1b5h.css';
import '../../css/s/shfdt_lyn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="q_3h0ub-d"/><path class="ml0cb1b5h"/><path class="shfdt_lyn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:panel-left-close-broken" /></template>
