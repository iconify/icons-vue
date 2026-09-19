<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dtzx5nj7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dtzx5nj7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-shuffle" /></template>
