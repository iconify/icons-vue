<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p3u4gobdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p3u4gobdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:vortex-logo-2" /></template>
