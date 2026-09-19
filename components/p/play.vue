<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w4257vbvt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="w4257vbvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:play" /></template>
