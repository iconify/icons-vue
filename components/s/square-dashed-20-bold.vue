<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ghzll71qg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ghzll71qg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:square-dashed-20-bold" /></template>
