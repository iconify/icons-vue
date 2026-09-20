<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pogosybms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pogosybms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:terminal-line" /></template>
