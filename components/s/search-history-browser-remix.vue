<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2u8nabzw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d2u8nabzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:search-history-browser-remix" /></template>
