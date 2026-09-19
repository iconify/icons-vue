<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mcq8mv15g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mcq8mv15g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:testimonial" /></template>
