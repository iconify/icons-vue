<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ngrep6yjk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ngrep6yjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:performance-increase" /></template>
