<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_ysxsbaw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":47,"height":26};
const content = `<path class="h_ysxsbaw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:wordmark-chat-26" /></template>
