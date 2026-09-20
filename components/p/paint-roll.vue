<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ss1lqj77n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ss1lqj77n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:paint-roll" /></template>
