<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zytj7im2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="zytj7im2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:zodiac-2-solid" /></template>
