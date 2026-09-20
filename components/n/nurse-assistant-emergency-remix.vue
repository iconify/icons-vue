<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cu4ad0blw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="cu4ad0blw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:nurse-assistant-emergency-remix" /></template>
