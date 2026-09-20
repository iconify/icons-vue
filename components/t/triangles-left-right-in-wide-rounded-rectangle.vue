<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7xoccxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="sv7xoccxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:triangles-left-right-in-wide-rounded-rectangle" /></template>
