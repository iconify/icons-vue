<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yng5jibsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yng5jibsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:share-1-filled" /></template>
