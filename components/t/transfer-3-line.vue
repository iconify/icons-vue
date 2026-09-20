<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pmu8so9_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pmu8so9_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:transfer-3-line" /></template>
