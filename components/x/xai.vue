<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f25tpeb8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f25tpeb8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:xai" /></template>
