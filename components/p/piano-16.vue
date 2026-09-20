<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w86kp8b-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="w86kp8b-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:piano-16" /></template>
