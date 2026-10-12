<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2a0yub0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r2a0yub0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:message-circle-reply-filled" /></template>
