<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rcosmutfq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="rcosmutfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:water-standpipe-with-handle-and-drinking-glass" /></template>
