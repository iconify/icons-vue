<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4d9xybyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="f4d9xybyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:user-astronaut" /></template>
