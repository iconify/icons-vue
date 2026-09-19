<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x9lrq2kct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="x9lrq2kct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:yin-yang" /></template>
