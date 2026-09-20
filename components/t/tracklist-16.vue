<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sdzcxgbks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="sdzcxgbks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:tracklist-16" /></template>
