<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u80r11ida.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="u80r11ida"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:radio-solid" /></template>
