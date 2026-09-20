<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j85y1pb5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="j85y1pb5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:stardust-above-outstretched-hand" /></template>
