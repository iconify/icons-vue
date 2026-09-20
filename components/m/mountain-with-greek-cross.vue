<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qs02qrb6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qs02qrb6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:mountain-with-greek-cross" /></template>
