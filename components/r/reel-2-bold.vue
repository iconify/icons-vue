<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yf3nmubio.css';
import '../../css/t/tjfdtw4pg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yf3nmubio"/><path clip-rule="evenodd" class="tjfdtw4pg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:reel-2-bold" /></template>
