<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yr1v6lfce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yr1v6lfce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:uplabs-logo-block" /></template>
