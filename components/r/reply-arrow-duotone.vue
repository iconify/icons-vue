<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wsooo9wze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary wsooo9wze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:reply-arrow-duotone" /></template>
