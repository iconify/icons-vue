<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e3-tfybox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e3-tfybox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:terminal-window-filled" /></template>
