<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dqr0jdrun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dqr0jdrun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:twitter-square" /></template>
