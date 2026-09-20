<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cvvcmoqrm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cvvcmoqrm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:remote-control-line" /></template>
