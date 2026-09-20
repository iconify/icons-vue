<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xc7hs2bbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xc7hs2bbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:planet-line" /></template>
