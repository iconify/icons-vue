<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/muky7dbqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="muky7dbqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:stratovolcano-smoke" /></template>
