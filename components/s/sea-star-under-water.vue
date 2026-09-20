<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_goq96ao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="d_goq96ao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:sea-star-under-water" /></template>
