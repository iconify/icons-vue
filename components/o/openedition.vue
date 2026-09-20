<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ys838abcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="ys838abcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:openedition" /></template>
