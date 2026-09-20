<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxgy6_bot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zxgy6_bot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:messages-bubble-text-bold" /></template>
