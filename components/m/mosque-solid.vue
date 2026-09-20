<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/owgf6abpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="owgf6abpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:mosque-solid" /></template>
