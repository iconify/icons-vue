<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y1oz6gbaq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="y1oz6gbaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:search-small-outline" /></template>
