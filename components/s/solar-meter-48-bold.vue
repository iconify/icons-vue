<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rvxin6bpa.css';
import '../../css/d/dnwij0b-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rvxin6bpa"/><path class="dnwij0b-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:solar-meter-48-bold" /></template>
