<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a5tyarwmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="a5tyarwmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:weight" /></template>
