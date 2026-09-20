<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hhtronb4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="hhtronb4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:send-email-remix" /></template>
