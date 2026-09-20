<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jk-p67bej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="jk-p67bej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:smiley-nauseas-solid" /></template>
