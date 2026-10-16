<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9jxscckh.css';
import '../../css/r/r83j7_bph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r9jxscckh"/><path class="r83j7_bph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:outage-map-48-bold" /></template>
