<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iyixm7aak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="iyixm7aak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:truck-moving" /></template>
