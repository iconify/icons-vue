<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d8hri9oyq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d8hri9oyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:swap-vertical-sharp" /></template>
