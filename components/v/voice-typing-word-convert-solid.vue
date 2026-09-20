<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dxoe_6bne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="dxoe_6bne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:voice-typing-word-convert-solid" /></template>
