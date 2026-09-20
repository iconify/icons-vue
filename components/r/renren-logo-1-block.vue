<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ly-8_lh2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ly-8_lh2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:renren-logo-1-block" /></template>
