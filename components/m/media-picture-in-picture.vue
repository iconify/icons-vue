<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pu-ic6bvo.css';
import '../../css/u/ujklyuwmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pu-ic6bvo"/><path class="ujklyuwmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:media-picture-in-picture" /></template>
