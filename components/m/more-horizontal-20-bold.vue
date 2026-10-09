<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mz8a-28-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mz8a-28-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:more-horizontal-20-bold" /></template>
