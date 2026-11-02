<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xzjix4l-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xzjix4l-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:settings-vertical-line" /></template>
