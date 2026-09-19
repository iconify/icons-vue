<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m6z9mmb0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":416};
const content = `<path class="m6z9mmb0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:star-half" /></template>
