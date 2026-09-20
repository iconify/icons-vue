<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o179kmblc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o179kmblc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nvidia-light" /></template>
