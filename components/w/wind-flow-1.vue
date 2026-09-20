<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/otcmcwblu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="otcmcwblu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:wind-flow-1" /></template>
