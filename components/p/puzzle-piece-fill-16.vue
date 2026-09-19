<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rdrx4h24c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rdrx4h24c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:puzzle-piece-fill-16" /></template>
