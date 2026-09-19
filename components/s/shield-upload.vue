<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqo7z6bak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hqo7z6bak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:shield-upload" /></template>
