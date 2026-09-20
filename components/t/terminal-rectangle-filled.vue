<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_nlz8qfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f_nlz8qfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:terminal-rectangle-filled" /></template>
