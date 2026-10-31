<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d9rhb9bhn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d9rhb9bhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:telegram-round" /></template>
