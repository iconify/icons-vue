<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d4i5-t89q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="d4i5-t89q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:octogon-16" /></template>
