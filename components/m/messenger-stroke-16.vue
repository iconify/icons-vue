<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i7dld0b_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="i7dld0b_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:messenger-stroke-16" /></template>
