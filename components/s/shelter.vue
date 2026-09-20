<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gpu8jptvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gpu8jptvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:shelter" /></template>
