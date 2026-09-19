<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pllr1xbqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pllr1xbqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:xt2-camera" /></template>
