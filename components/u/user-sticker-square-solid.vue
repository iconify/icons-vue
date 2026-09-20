<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c8nyzz8mt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="c8nyzz8mt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:user-sticker-square-solid" /></template>
