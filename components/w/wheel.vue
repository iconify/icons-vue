<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hwwpx0b3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="hwwpx0b3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:wheel" /></template>
