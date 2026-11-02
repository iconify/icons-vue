<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dtayzgbcl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dtayzgbcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:watch-2-fill" /></template>
