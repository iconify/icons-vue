<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-vkctb7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="r-vkctb7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:voice-scan-2-remix" /></template>
