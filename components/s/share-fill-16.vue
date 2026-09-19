<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fpy7t5tbp.css';
import '../../css/j/j2y13v5ma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fpy7t5tbp"/><path class="j2y13v5ma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:share-fill-16" /></template>
