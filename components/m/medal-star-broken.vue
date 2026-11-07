<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/j/j8ful4bxb.css';
import '../../css/r/ryhgqrraa.css';
import '../../css/v/v7q1lwidl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="j8ful4bxb"/><path class="ryhgqrraa"/><path class="v7q1lwidl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:medal-star-broken" /></template>
