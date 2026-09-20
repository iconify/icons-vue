<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uxwq50j8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uxwq50j8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:twitch" /></template>
