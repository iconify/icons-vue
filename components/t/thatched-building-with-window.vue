<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j9im-ib6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="j9im-ib6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:thatched-building-with-window" /></template>
