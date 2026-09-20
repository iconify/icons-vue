<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wap2w4btr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="wap2w4btr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:nurse-assistant-emergency-remix" /></template>
