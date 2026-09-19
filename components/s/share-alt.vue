<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-keh5bfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="n-keh5bfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:share-alt" /></template>
