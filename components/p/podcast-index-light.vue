<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fa6e78afl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fa6e78afl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:podcast-index-light" /></template>
