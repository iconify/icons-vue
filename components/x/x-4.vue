<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cd4icx4ma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cd4icx4ma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:x-4" /></template>
