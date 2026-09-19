<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-__ckyep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="h-__ckyep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:smiley" /></template>
