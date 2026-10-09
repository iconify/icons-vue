<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xfqlvd-8s.css';
import '../../css/k/kaoreac1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xfqlvd-8s"/><path class="kaoreac1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:rotate-ccw-48" /></template>
