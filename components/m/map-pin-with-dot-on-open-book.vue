<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fz8ow6yfn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="fz8ow6yfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:map-pin-with-dot-on-open-book" /></template>
