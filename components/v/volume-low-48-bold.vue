<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kc5lbibdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kc5lbibdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:volume-low-48-bold" /></template>
