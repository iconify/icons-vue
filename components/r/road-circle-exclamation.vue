<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ch8tc1bak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ch8tc1bak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:road-circle-exclamation" /></template>
