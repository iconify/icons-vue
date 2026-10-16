<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cn7efoaca.css';
import '../../css/f/f56ez5bwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cn7efoaca"/><path class="f56ez5bwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:zero-emissions-48-bold" /></template>
