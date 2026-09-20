<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lnykedbvb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lnykedbvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:willow-dark" /></template>
