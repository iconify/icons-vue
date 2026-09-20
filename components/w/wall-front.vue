<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o9g2sprop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="o9g2sprop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:wall-front" /></template>
