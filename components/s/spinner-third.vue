<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u1onwk--p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="u1onwk--p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:spinner-third" /></template>
