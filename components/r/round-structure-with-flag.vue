<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d5q5vuphz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="d5q5vuphz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:round-structure-with-flag" /></template>
