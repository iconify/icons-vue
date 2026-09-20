<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vbk7jibmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vbk7jibmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:rewind-backward-square-5-line" /></template>
