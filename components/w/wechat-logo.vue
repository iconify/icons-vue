<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mjehtdb3z.css';
import '../../css/y/ys0-a9buz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mjehtdb3z"/><path class="ys0-a9buz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:wechat-logo" /></template>
