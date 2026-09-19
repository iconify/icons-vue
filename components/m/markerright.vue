<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/urgc0zbwo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":768};
const content = `<path class="urgc0zbwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:markerright" /></template>
