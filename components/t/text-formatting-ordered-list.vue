<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o2qncv8ux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="o2qncv8ux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:text-formatting-ordered-list" /></template>
