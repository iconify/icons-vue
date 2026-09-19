<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yil8wdbam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="yil8wdbam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:peseta-sign" /></template>
