<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/se3r-mb6s.css';
import '../../css/f/fecdmsb2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="se3r-mb6s"/><path class="fecdmsb2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:university-48-bold" /></template>
