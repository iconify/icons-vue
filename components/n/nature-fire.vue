<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yjse0jekj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="yjse0jekj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:nature-fire" /></template>
