<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eb2y1ebum.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="eb2y1ebum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:tooltip-start-alert" /></template>
