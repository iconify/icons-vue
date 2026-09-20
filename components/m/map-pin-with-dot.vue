<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rx9b28b0k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="rx9b28b0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:map-pin-with-dot" /></template>
