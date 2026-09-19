<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zcc6q1bxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="zcc6q1bxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:pied-piper-square" /></template>
