<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kay7cvccb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="kay7cvccb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:pytest-wordmark" /></template>
