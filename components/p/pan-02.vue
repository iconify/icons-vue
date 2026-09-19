<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/x/xrl_5-b0c.css';
import '../../css/b/b_10b0_-a.css';
import '../../css/q/qn8_xfbjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="xrl_5-b0c"/><path class="b_10b0_-a"/><path class="qn8_xfbjc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:pan-02" /></template>
