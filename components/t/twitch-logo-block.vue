<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xm9mqfb5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xm9mqfb5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:twitch-logo-block" /></template>
