<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vl00rlbhk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vl00rlbhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:music-note" /></template>
