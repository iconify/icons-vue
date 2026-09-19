<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g7qhb_-hh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="g7qhb_-hh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:stats-bars2" /></template>
