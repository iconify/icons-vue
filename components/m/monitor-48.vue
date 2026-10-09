<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xszfmab4u.css';
import '../../css/e/ezx2ctbsk.css';
import '../../css/n/nh3pp-bwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xszfmab4u"/><path class="ezx2ctbsk"/><path class="nh3pp-bwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:monitor-48" /></template>
