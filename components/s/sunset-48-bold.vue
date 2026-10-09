<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/srxxy_b0g.css';
import '../../css/v/va3-tmdaw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="srxxy_b0g"/><path class="va3-tmdaw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sunset-48-bold" /></template>
