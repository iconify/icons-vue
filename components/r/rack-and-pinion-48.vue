<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nj8ilnbfl.css';
import '../../css/t/t4mrhvxik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nj8ilnbfl"/><path class="t4mrhvxik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:rack-and-pinion-48" /></template>
