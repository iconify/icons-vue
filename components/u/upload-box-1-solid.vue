<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_3nmhnxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="i_3nmhnxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:upload-box-1-solid" /></template>
