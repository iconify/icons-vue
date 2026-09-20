<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p9rtbeb4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p9rtbeb4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:toggle-right-2-fill" /></template>
