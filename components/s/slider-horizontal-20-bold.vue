<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kysafccpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kysafccpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:slider-horizontal-20-bold" /></template>
