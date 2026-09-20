<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/relpmcc5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="relpmcc5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:pencil" /></template>
