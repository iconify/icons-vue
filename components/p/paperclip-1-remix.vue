<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ycy_c2baw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="ycy_c2baw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:paperclip-1-remix" /></template>
