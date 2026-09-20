<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7d751fdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="l7d751fdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:voice-mail-solid" /></template>
