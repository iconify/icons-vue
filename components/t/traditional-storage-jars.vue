<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i1vnq8g0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="i1vnq8g0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:traditional-storage-jars" /></template>
