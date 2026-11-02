<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/clzhi9brf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="clzhi9brf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:microphone-line" /></template>
