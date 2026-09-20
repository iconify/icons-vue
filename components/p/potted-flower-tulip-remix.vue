<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vfpp48ogo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="vfpp48ogo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:potted-flower-tulip-remix" /></template>
