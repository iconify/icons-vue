<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r89124h4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="r89124h4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:microphone-slash" /></template>
