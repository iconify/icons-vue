<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jzq1-xdkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jzq1-xdkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:quarry-48" /></template>
