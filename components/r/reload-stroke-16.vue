<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/id4ivymod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="id4ivymod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:reload-stroke-16" /></template>
