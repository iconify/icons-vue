<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/msez2ntih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":585,"height":684};
const content = `<path class="msez2ntih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:play" /></template>
