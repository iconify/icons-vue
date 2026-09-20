<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iczf7mbbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="iczf7mbbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:sheets" /></template>
