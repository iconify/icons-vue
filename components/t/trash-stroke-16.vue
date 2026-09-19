<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezshxbbzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ezshxbbzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:trash-stroke-16" /></template>
