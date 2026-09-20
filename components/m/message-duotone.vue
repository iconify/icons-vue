<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/do7-vznlq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="do7-vznlq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:message-duotone" /></template>
