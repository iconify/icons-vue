<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6zsho01p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f6zsho01p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:telegram-logo-2-solid" /></template>
