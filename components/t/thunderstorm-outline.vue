<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vw_3i8bof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vw_3i8bof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:thunderstorm-outline" /></template>
