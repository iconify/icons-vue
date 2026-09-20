<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i67z77bnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="i67z77bnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:notification-application-1-solid" /></template>
