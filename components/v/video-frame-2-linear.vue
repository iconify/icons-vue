<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k09b0rb4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k09b0rb4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:video-frame-2-linear" /></template>
