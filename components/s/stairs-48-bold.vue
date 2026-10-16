<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oj6wo8kgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="oj6wo8kgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:stairs-48-bold" /></template>
