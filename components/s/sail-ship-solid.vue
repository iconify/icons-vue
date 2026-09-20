<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czzlbxmws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="czzlbxmws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:sail-ship-solid" /></template>
