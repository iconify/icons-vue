<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f3p6v5b5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="f3p6v5b5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:text-stroke-16" /></template>
