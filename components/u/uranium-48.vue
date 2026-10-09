<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z5-sh3vvp.css';
import '../../css/j/joigvlfvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z5-sh3vvp"/><path class="joigvlfvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:uranium-48" /></template>
