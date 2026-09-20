<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yt_77-bpl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yt_77-bpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:text-font-size" /></template>
