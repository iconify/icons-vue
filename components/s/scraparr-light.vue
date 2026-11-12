<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ac7w55bfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ac7w55bfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:scraparr-light" /></template>
