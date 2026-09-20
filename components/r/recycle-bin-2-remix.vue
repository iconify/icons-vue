<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fsomw9b0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="fsomw9b0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:recycle-bin-2-remix" /></template>
