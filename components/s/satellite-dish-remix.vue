<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xxj7zfbpg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="xxj7zfbpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:satellite-dish-remix" /></template>
