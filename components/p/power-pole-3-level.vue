<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fw_2ghb4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fw_2ghb4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:power-pole-3-level" /></template>
