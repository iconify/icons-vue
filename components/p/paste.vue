<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fnw7i4b4q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fnw7i4b4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:paste" /></template>
