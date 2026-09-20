<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yusenx73p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yusenx73p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:message-settings-outline" /></template>
