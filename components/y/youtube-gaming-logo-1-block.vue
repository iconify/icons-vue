<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i8l2rutlg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i8l2rutlg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:youtube-gaming-logo-1-block" /></template>
