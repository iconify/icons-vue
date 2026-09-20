<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lclv7ft7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lclv7ft7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:microsoft-yammer-logo-1" /></template>
