<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uy-z67b1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uy-z67b1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-download" /></template>
