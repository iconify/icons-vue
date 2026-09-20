<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rwx5zpbpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="rwx5zpbpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:marker-stroked-15" /></template>
