<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ua0op0ati.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ua0op0ati"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:stratovolcano-smoke-2" /></template>
