<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ygd9qibvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ygd9qibvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:screen-wide" /></template>
