<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/m/m1bq1f0kg.css';
import '../../css/t/tq3b1t0jd.css';
import '../../css/b/bw0_yfvdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="m1bq1f0kg"/><path class="tq3b1t0jd"/><path class="bw0_yfvdf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:plug-01" /></template>
