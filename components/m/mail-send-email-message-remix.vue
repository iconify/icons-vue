<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hmu1be8bm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="hmu1be8bm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:mail-send-email-message-remix" /></template>
