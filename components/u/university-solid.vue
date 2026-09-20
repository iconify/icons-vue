<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/witrdgbhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="witrdgbhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:university-solid" /></template>
