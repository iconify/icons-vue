<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kwpeto0yu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="kwpeto0yu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:spiral-shape-solid" /></template>
