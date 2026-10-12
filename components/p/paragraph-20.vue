<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dc9t6kiho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dc9t6kiho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:paragraph-20" /></template>
