<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qnaelyb2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="qnaelyb2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:shell-window-minimize-filled" /></template>
