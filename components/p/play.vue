<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m39f0nb9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="m39f0nb9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:play" /></template>
