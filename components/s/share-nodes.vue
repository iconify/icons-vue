<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g5n500bfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="g5n500bfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:share-nodes" /></template>
