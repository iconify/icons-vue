<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lr_xxwbkp.css';
import '../../css/j/jyvikwbnh.css';
import '../../css/w/w3xf5cbjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lr_xxwbkp"/><path class="jyvikwbnh"/><path class="w3xf5cbjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:search-circle-outline" /></template>
