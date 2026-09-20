<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cd6hm15ed.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cd6hm15ed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump-color:mail-send-email-message-flat" /></template>
