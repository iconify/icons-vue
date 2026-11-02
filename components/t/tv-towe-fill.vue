<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cw08exeux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cw08exeux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:tv-towe-fill" /></template>
