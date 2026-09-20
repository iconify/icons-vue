<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mxw-lso_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="mxw-lso_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:smiley-very-shocked-solid" /></template>
