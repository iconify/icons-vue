<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ia7ydhbcf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="ia7ydhbcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:monitor" /></template>
