<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r4knz0mmr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="r4knz0mmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:memorial-stone-with-question-mark" /></template>
