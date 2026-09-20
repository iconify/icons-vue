<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/upje9sbah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="upje9sbah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:redo-solid" /></template>
