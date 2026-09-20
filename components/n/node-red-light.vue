<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ru6tesmyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ru6tesmyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:node-red-light" /></template>
