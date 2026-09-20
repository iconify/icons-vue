<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wz1o6hb3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="wz1o6hb3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:navigation-arrow-off" /></template>
