<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vtawmliso.css';
import '../../css/u/ulvnhe8jo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vtawmliso"/><path class="ulvnhe8jo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pizza-slice-48" /></template>
