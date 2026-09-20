<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j04ijnb3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="j04ijnb3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:p-arrow-up" /></template>
