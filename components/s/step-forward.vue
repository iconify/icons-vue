<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/roc7g_b5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="roc7g_b5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:step-forward" /></template>
