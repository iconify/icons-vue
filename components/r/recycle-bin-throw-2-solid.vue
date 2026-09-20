<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ocqkor64e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ocqkor64e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:recycle-bin-throw-2-solid" /></template>
