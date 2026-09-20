<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pmu75ol-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pmu75ol-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:one-diamond-solid" /></template>
