<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mjzn3h8oq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mjzn3h8oq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:star-rating-48" /></template>
