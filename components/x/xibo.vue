<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lw50d4b0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lw50d4b0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:xibo" /></template>
