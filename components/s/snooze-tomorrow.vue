<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xbmeb0b8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xbmeb0b8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:snooze-tomorrow" /></template>
