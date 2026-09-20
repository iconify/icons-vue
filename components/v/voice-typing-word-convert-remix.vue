<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wor_cd2ux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="wor_cd2ux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:voice-typing-word-convert-remix" /></template>
