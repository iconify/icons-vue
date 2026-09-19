<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vnir39bzm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vnir39bzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:twitter-stroke-16" /></template>
