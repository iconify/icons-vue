<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/otu-ipbqt.css';
import '../../css/q/q1xmknq-a.css';
import '../../css/s/s50abdb3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="otu-ipbqt"/><path class="q1xmknq-a"/><path class="s50abdb3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wind-turbine-off-48-bold" /></template>
