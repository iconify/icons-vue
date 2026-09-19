<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kn199flym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kn199flym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-arrow-forward" /></template>
