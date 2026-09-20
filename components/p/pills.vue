<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ngpdcebgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ngpdcebgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:pills" /></template>
