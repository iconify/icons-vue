<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/prdpuebmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1536};
const content = `<path class="prdpuebmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:map-marker" /></template>
