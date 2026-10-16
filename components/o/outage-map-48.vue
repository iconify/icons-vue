<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rvjwhfbog.css';
import '../../css/e/ef6a7mfgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rvjwhfbog"/><path class="ef6a7mfgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:outage-map-48" /></template>
