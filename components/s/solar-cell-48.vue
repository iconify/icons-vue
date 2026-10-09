<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b6fb_actj.css';
import '../../css/r/rtr4tcjzi.css';
import '../../css/a/agvxs4kjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b6fb_actj"/><path class="rtr4tcjzi"/><path class="agvxs4kjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:solar-cell-48" /></template>
