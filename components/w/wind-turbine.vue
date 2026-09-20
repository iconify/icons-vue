<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k20y2qbch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k20y2qbch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:wind-turbine" /></template>
