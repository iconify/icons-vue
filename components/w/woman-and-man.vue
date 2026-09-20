<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/try1uhstd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="try1uhstd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:woman-and-man" /></template>
