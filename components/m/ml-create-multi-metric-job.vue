<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3-2ppbxq.css';
import '../../css/s/sc7gseb_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ouiIcon__fillSecondary r3-2ppbxq"/><path class="sc7gseb_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:ml-create-multi-metric-job" /></template>
