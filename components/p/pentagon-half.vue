<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/waetc2bmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="waetc2bmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:pentagon-half" /></template>
