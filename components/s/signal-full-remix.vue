<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xmpdv0f8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="xmpdv0f8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:signal-full-remix" /></template>
