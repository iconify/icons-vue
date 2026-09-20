<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-sx8hbwt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x-sx8hbwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:taobao-fill" /></template>
