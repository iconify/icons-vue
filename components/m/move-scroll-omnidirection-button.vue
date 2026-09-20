<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o9noqwb9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o9noqwb9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:move-scroll-omnidirection-button" /></template>
