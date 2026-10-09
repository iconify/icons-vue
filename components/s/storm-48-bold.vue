<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uea8u9cfl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uea8u9cfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:storm-48-bold" /></template>
