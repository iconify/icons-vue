<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vjsuzrt7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vjsuzrt7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:tablet-fill" /></template>
