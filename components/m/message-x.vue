<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/st61j9bfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="st61j9bfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:message-x" /></template>
