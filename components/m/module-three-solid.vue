<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xgc3b8bjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="xgc3b8bjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:module-three-solid" /></template>
