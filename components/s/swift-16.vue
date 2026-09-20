<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vo5l4obau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vo5l4obau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nonicons:swift-16" /></template>
