<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/imewvslhu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="imewvslhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:tarp-droplet" /></template>
