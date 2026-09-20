<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wh4x1nwdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wh4x1nwdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:semaphore-dark" /></template>
