<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u0e143blo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1632,"height":1792};
const content = `<path class="u0e143blo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:sort-alpha-asc" /></template>
