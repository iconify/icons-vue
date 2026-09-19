<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/quypo_bot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="quypo_bot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:monitor-wallpaper-filled" /></template>
