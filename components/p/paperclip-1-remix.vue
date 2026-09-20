<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g6u7xabka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g6u7xabka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:paperclip-1-remix" /></template>
