<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z4y603qxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="z4y603qxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:pause" /></template>
