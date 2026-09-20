<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fv9z5ty7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="fv9z5ty7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:pedestrian" /></template>
