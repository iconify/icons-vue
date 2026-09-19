<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j64ylkbiy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="j64ylkbiy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:videocam" /></template>
