<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wgzcs4-ej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="wgzcs4-ej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:smiley-emoji-kiss-nervous-solid" /></template>
