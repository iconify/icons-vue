<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p1nyrhk2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="p1nyrhk2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:map-marker" /></template>
