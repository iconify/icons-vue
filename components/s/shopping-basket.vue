<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e2tucol5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="e2tucol5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:shopping-basket" /></template>
