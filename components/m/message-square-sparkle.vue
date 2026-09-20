<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/orjfbkblo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="orjfbkblo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:message-square-sparkle" /></template>
