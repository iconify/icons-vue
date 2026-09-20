<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-q_8qb4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e-q_8qb4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:skeleton" /></template>
