<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fcag5bcei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="fcag5bcei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:raspberrypi-wordmark" /></template>
