<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yboxb49-l.css';
import '../../css/p/pbutksb1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yboxb49-l"/><path class="pbutksb1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:snapchat-square" /></template>
