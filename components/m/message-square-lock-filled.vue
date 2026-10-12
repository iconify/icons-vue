<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xq20y-biq.css';
import '../../css/y/yv4alofav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xq20y-biq"/><path clip-rule="evenodd" class="yv4alofav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:message-square-lock-filled" /></template>
