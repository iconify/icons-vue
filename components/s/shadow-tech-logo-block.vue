<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tcskt3amy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tcskt3amy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:shadow-tech-logo-block" /></template>
