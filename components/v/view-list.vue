<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y5q44-hod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="y5q44-hod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:view-list" /></template>
