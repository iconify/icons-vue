<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tpwpmd72b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="tpwpmd72b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:rotatecounterclockwise" /></template>
