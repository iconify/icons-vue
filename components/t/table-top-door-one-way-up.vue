<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xe5x2sqyg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="xe5x2sqyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:table-top-door-one-way-up" /></template>
