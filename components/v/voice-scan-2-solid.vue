<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t6-shre9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="t6-shre9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:voice-scan-2-solid" /></template>
