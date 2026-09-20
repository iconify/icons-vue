<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ovbmp5yxh.css';
import '../../css/y/yt306rbnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ovbmp5yxh"/><path class="yt306rbnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:system-search-filled" /></template>
