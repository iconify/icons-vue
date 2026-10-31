<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wbbqp8bsh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wbbqp8bsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:navigation-alt-fill-round" /></template>
