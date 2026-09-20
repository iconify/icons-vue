<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8i-_-z1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="h8i-_-z1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:volume-medium" /></template>
