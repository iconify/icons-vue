<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rz4d19ipl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rz4d19ipl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:turning-loop" /></template>
