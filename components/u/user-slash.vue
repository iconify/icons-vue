<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ncczvnomg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="ncczvnomg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:user-slash" /></template>
