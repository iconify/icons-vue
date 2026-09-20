<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gby07cowi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="gby07cowi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:new-sticky-note-solid" /></template>
