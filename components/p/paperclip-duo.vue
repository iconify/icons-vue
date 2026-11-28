<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6s0e3buf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j6s0e3buf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:paperclip-duo" /></template>
