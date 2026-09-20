<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yha1vyqkk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yha1vyqkk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:page-setting-remix" /></template>
