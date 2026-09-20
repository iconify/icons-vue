<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tmgzy2b3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tmgzy2b3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:nature-cloudy" /></template>
