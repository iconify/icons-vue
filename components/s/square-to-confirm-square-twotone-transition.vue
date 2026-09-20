<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iw1iew.css';
import '../../css/y/y591zt.css';
import '../../css/k/kofr8g.css';
import '../../css/f/fill-from-0.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iw1iew y591zt"/><path class="iw1iew kofr8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:square-to-confirm-square-twotone-transition" /></template>
