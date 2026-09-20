<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sfan8ddsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sfan8ddsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:move-1" /></template>
