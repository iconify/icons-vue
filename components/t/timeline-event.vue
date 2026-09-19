<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/glp9_tbpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="glp9_tbpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:timeline-event" /></template>
