<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wkxh5bcsi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wkxh5bcsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:paperclip-filled" /></template>
