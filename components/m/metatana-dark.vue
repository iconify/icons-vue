<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j9j_y2-pq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j9j_y2-pq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:metatana-dark" /></template>
