<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wv538wbvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wv538wbvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:speaker-line" /></template>
