<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wg_564d1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="wg_564d1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:voice-activation-check-validate-remix" /></template>
