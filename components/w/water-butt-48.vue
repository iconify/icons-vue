<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kdvp-0bcn.css';
import '../../css/h/hbbh9n7le.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kdvp-0bcn"/><path class="hbbh9n7le"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:water-butt-48" /></template>
