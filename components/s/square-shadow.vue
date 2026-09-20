<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xcrgqg1rz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xcrgqg1rz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:square-shadow" /></template>
