<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zdojnbc8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zdojnbc8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:play" /></template>
