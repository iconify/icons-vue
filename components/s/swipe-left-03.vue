<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xak_anbgz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xak_anbgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:swipe-left-03" /></template>
