<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zg37cactp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zg37cactp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:spade" /></template>
