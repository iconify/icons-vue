<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qd2y4rqwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qd2y4rqwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:people" /></template>
