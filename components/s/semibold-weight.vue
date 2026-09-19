<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/horqr3d3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="horqr3d3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:semibold-weight" /></template>
