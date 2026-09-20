<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p5_w49avu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="p5_w49avu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:mail-send-email-message-circle-solid" /></template>
