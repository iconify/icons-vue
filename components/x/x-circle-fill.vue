<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w6e0m7bry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="w6e0m7bry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:x-circle-fill" /></template>
