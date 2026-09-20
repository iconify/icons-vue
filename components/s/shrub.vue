<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l8udzeb7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="l8udzeb7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:shrub" /></template>
