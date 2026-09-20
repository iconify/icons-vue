<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xv0tkkeho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xv0tkkeho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:snapchat-fill" /></template>
