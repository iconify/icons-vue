<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ngt5p8b-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="ngt5p8b-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:star-2" /></template>
