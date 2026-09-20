<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/daormvd9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="daormvd9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:table-top-door-secret-vertical" /></template>
