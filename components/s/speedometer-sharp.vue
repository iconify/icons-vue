<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w9p5mvjco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w9p5mvjco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:speedometer-sharp" /></template>
