<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dz--4khft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="dz--4khft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:squarea" /></template>
