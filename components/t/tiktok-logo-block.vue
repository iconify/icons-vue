<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jk8b46bza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jk8b46bza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:tiktok-logo-block" /></template>
