<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vrpvxrlxf.css';
import '../../css/p/py4nxfbnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vrpvxrlxf"/><path class="py4nxfbnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sun-check-48" /></template>
