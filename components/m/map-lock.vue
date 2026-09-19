<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-1k3_b2n.css';
import '../../css/q/qjd9umv4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="z-1k3_b2n"/><path class="qjd9umv4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:map-lock" /></template>
