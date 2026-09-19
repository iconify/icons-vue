<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yzhyzjbhq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="yzhyzjbhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:social-squidoo" /></template>
