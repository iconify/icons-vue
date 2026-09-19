<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fy_3j5b9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="fy_3j5b9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:tree" /></template>
