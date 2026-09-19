<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hxs9e9bmx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hxs9e9bmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:rocket" /></template>
