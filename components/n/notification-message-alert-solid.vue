<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qrj_-3b2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="qrj_-3b2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:notification-message-alert-solid" /></template>
