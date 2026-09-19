<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rirmlzcsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="rirmlzcsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:teleport-wordmark" /></template>
