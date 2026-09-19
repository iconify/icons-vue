<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dirql1bho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="dirql1bho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:shapes-stroke-12" /></template>
