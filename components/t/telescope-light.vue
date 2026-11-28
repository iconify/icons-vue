<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gy_ggab6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="gy_ggab6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:telescope-light" /></template>
