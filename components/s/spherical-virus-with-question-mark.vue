<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y05ag6itt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="y05ag6itt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:spherical-virus-with-question-mark" /></template>
