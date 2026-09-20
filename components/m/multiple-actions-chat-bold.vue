<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y0yqaacfm.css';
import '../../css/g/g4ri23blu.css';
import '../../css/h/hovqi_wid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y0yqaacfm"/><path class="g4ri23blu"/><path class="hovqi_wid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:multiple-actions-chat-bold" /></template>
