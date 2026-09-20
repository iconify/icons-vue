<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wev7_1bhi.css';
import '../../css/y/yz-efebcs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wev7_1bhi"/><path class="yz-efebcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:square-minus" /></template>
