<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/le-81vboo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="le-81vboo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:pin" /></template>
