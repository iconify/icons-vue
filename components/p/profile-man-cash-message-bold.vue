<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w70p-uwcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w70p-uwcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:profile-man-cash-message-bold" /></template>
