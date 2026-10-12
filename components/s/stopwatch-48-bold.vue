<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ij6cj4rwy.css';
import '../../css/i/iqxu07b4z.css';
import '../../css/u/uz1rh-b9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ij6cj4rwy"/><path class="iqxu07b4z"/><path class="uz1rh-b9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:stopwatch-48-bold" /></template>
