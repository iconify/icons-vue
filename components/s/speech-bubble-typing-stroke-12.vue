<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ow2_qqxpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ow2_qqxpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:speech-bubble-typing-stroke-12" /></template>
