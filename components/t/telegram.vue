<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d3wm8ghmk.css';
import '../../css/c/c6ogy1b5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d3wm8ghmk"/><path class="c6ogy1b5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:telegram" /></template>
