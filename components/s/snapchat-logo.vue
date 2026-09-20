<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezfb-7blg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ezfb-7blg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:snapchat-logo" /></template>
