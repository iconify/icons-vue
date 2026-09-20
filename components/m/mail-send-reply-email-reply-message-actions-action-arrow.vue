<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jy_9vu8he.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="jy_9vu8he"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:mail-send-reply-email-reply-message-actions-action-arrow" /></template>
