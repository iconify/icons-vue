<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kwzby5b2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="kwzby5b2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:moodle-square" /></template>
