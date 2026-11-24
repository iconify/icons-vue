<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j4aycwbjj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j4aycwbjj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:trawl-light" /></template>
