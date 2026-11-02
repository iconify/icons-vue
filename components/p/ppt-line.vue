<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xkdd5oshq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xkdd5oshq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:ppt-line" /></template>
