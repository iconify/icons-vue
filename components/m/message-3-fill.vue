<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w71pim13w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w71pim13w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:message-3-fill" /></template>
