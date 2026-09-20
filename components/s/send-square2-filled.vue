<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vkfonmbcs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vkfonmbcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:send-square2-filled" /></template>
