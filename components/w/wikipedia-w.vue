<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v79c05byr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="v79c05byr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:wikipedia-w" /></template>
