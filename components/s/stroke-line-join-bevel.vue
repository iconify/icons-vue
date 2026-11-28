<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/obv-dzbot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="obv-dzbot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:stroke-line-join-bevel" /></template>
