<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tywfxp2wn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="tywfxp2wn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:smiley-surprised-solid" /></template>
