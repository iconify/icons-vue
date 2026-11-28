<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9-2w9czx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e9-2w9czx primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:move-duotone" /></template>
