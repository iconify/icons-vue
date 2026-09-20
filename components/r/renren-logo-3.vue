<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bx_j1xbmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bx_j1xbmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:renren-logo-3" /></template>
