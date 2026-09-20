<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wite9bc0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="wite9bc0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:wave-signal-circle-remix" /></template>
