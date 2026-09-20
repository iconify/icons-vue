<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jnhk24nnz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jnhk24nnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:puzzle-piece" /></template>
