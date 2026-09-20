<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gj7-ocbzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gj7-ocbzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:wreath-line" /></template>
