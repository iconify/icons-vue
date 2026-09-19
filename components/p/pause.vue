<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zqci6gbsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="zqci6gbsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:pause" /></template>
