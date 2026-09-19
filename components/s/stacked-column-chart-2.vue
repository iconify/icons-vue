<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jnw1cjxky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="jnw1cjxky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:stacked-column-chart-2" /></template>
