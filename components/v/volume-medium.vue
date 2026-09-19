<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/raliu5b3x.css';
import '../../css/d/d1olnibrd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="raliu5b3x"/><path class="d1olnibrd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:volume-medium" /></template>
