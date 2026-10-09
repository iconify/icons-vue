<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3wp5cowp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y3wp5cowp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:power-off-48" /></template>
