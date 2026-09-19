<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w12d0osrh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="w12d0osrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:vuejs-wordmark" /></template>
