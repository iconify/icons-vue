<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yqlzzl8-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="yqlzzl8-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:watch-circle-charging-remix" /></template>
