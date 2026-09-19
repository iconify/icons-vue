<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cu9qb8bzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="cu9qb8bzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:vyper-wordmark" /></template>
