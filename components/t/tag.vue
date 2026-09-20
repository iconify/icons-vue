<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tjf5vubbf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tjf5vubbf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:tag" /></template>
