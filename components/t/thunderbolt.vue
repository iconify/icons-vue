<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tztkk4_1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="tztkk4_1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:thunderbolt" /></template>
