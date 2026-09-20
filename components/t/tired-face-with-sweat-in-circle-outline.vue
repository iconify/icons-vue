<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lrnnfb6_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="lrnnfb6_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:tired-face-with-sweat-in-circle-outline" /></template>
