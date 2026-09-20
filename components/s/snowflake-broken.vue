<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/t/txk6dwbhy.css';
import '../../css/z/zipqmpboj.css';
import '../../css/n/nlvmx70rd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="txk6dwbhy"/><path class="zipqmpboj"/><path class="nlvmx70rd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:snowflake-broken" /></template>
