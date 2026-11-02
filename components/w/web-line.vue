<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qwfm1uuyo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qwfm1uuyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:web-line" /></template>
