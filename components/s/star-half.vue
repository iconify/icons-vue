<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rawlm3oon.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="rawlm3oon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:star-half" /></template>
