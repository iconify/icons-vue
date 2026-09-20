<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/au8ux7_ws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="au8ux7_ws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:water-from-pipe" /></template>
