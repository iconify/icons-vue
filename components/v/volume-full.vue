<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n30xjkbmn.css';
import '../../css/f/ft3afwb6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n30xjkbmn"/><path class="ft3afwb6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:volume-full" /></template>
