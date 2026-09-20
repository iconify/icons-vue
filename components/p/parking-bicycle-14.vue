<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xj5nrubhr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="xj5nrubhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:parking-bicycle-14" /></template>
