<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fofqrabvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fofqrabvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:spark-line" /></template>
