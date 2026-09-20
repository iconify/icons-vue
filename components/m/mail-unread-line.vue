<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/otoo-_9fi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="otoo-_9fi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:mail-unread-line" /></template>
