<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ad1b9_ipc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ad1b9_ipc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:mail-send-envelope-solid" /></template>
