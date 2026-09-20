<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4nw3wu7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v4nw3wu7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:voice-typing-word-convert-solid" /></template>
