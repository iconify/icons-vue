<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qlxb7bcwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qlxb7bcwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:page-break-remix" /></template>
