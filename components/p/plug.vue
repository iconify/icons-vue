<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vl-az0bur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vl-az0bur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:plug" /></template>
