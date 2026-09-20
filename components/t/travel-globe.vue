<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sh7c1-bqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="sh7c1-bqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:travel-globe" /></template>
