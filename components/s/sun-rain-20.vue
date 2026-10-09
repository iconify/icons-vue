<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt41qcbim.css';
import '../../css/d/d122lmxog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dt41qcbim"/><path class="d122lmxog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sun-rain-20" /></template>
