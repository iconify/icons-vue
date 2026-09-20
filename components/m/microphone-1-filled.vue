<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvk2tb3ud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nvk2tb3ud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:microphone-1-filled" /></template>
