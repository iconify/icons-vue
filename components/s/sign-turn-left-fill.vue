<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zy51f2wrm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zy51f2wrm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:sign-turn-left-fill" /></template>
