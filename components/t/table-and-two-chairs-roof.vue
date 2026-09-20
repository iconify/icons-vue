<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kpjxycb8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kpjxycb8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:table-and-two-chairs-roof" /></template>
