<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tb8m4hn8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="tb8m4hn8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:qr-code-solid" /></template>
