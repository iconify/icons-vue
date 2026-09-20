<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g7ml_9bwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g7ml_9bwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:twitter-logo-2-block" /></template>
