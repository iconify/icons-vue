<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h2pim1bhl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h2pim1bhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:message-square-reply-fill" /></template>
