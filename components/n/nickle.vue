<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-rfoac0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r-rfoac0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:nickle" /></template>
