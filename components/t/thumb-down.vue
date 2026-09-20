<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d5z-4-bht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="d5z-4-bht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:thumb-down" /></template>
