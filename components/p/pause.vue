<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bh930abre.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bh930abre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:pause" /></template>
