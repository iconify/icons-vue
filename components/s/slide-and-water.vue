<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sdxu77b3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="sdxu77b3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:slide-and-water" /></template>
