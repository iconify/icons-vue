<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y4r9pjegb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="y4r9pjegb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:restaurant-noodle" /></template>
