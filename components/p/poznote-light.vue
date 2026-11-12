<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hfat7mbwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hfat7mbwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:poznote-light" /></template>
