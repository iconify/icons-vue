<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/chivyabpi.css';
import '../../css/u/u7007_xth.css';
import '../../css/h/h_ntzgbew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="chivyabpi"/><path class="u7007_xth"/><path class="h_ntzgbew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:transformer-pole-48-bold" /></template>
