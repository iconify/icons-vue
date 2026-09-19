<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/ws7z_-boi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="ws7z_-boi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:twocolumnsleftalt" /></template>
