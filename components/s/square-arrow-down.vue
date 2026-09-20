<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i3v1tk3gr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i3v1tk3gr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:square-arrow-down" /></template>
