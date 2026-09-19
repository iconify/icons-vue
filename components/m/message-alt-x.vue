<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rrrju3b8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rrrju3b8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:message-alt-x" /></template>
