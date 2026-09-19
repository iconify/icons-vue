<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lysg5zyhu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lysg5zyhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:view-sidebar-left" /></template>
