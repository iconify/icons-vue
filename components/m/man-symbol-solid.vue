<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vnvm2tb2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="vnvm2tb2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:man-symbol-solid" /></template>
