<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/giwi5ubbg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="giwi5ubbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:warning" /></template>
