<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/idh8nnbdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="idh8nnbdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:stool" /></template>
