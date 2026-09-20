<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k64a_t5ri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="k64a_t5ri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:wind" /></template>
