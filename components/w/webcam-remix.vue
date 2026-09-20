<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mt9sv002d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="mt9sv002d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:webcam-remix" /></template>
