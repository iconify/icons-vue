<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jekpe8lyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jekpe8lyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sparkles-20" /></template>
