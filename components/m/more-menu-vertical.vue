<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xd5y4xbre.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xd5y4xbre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:more-menu-vertical" /></template>
