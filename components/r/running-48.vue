<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4s6aob2m.css';
import '../../css/n/n0xyitehn.css';
import '../../css/w/w3e274hyt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s4s6aob2m"/><path class="n0xyitehn"/><path class="w3e274hyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:running-48" /></template>
