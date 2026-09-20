<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-8zs4kug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="l-8zs4kug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:pyramid" /></template>
