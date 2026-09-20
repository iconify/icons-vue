<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/odwxg8bki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="odwxg8bki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:star-half-right-o" /></template>
