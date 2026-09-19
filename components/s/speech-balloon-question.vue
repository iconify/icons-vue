<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mirhpy0av.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="mirhpy0av"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:speech-balloon-question" /></template>
