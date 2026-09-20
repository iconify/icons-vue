<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aem1l6blz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="aem1l6blz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:tooltip-start-text" /></template>
