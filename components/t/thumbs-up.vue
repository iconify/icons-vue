<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pg07ajpns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pg07ajpns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:thumbs-up" /></template>
