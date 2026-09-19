<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rn6481bwr.css';
import '../../css/p/pxkrmsbhi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rn6481bwr"/><path class="pxkrmsbhi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:temperature-min" /></template>
