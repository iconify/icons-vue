<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ondu0mjsi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ondu0mjsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:mouse-smart-bold" /></template>
