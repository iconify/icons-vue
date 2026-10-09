<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wxvl6gbzy.css';
import '../../css/i/i-5u2oj8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wxvl6gbzy"/><path class="i-5u2oj8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:move-vertical-20" /></template>
