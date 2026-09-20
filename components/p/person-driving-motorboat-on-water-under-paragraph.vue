<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sh23lb5bp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="sh23lb5bp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-driving-motorboat-on-water-under-paragraph" /></template>
