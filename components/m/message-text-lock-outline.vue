<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lbnm2ob4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lbnm2ob4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:message-text-lock-outline" /></template>
