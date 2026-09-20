<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vgt_puboq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="vgt_puboq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:mouse-remix" /></template>
