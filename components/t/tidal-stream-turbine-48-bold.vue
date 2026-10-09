<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmxj-_ahy.css';
import '../../css/m/muoaj3btf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wmxj-_ahy"/><path class="muoaj3btf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tidal-stream-turbine-48-bold" /></template>
