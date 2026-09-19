<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iulg5_bre.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="iulg5_bre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:redis-wordmark" /></template>
