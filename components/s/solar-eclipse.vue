<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f06ytdb_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="f06ytdb_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:solar-eclipse" /></template>
