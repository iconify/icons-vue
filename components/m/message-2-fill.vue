<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bhpi9jbet.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bhpi9jbet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:message-2-fill" /></template>
