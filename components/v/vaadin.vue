<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fraqy9bow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fraqy9bow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:vaadin" /></template>
