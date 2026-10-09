<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qee7o7hwy.css';
import '../../css/r/rchtrhc_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qee7o7hwy"/><path class="rchtrhc_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:map-48-bold" /></template>
