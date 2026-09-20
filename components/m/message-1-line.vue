<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jy-g8lbjc.css';
import '../../css/t/tykix6bve.css';
import '../../css/p/p9m9lkbmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jy-g8lbjc"/><path class="tykix6bve"/><path class="p9m9lkbmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:message-1-line" /></template>
