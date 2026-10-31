<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d9u8yg5wu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d9u8yg5wu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:reply-all-duotone-round" /></template>
