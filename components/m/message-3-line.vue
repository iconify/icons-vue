<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jy-g8lbjc.css';
import '../../css/i/i99p7sv5h.css';
import '../../css/p/p9m9lkbmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jy-g8lbjc"/><path class="i99p7sv5h"/><path class="p9m9lkbmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:message-3-line" /></template>
