<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vs4k1rbmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vs4k1rbmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:scan-face" /></template>
