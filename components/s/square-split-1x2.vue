<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/st0_9e3qq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="st0_9e3qq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:square-split-1x2" /></template>
