<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ycr268boj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ycr268boj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:map-unlocked-filled" /></template>
