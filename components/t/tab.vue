<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ri6cgf8wi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ri6cgf8wi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:tab" /></template>
