<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-_75wncl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="c-_75wncl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:party-popper-solid" /></template>
