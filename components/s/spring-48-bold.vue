<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gu067ebme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gu067ebme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:spring-48-bold" /></template>
