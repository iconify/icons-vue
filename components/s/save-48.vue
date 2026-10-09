<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x7_yqvbof.css';
import '../../css/v/vf15g1hye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x7_yqvbof"/><path class="vf15g1hye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:save-48" /></template>
