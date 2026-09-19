<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u9a0f9bjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="u9a0f9bjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:trello" /></template>
