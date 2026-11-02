<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w4jx25u4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w4jx25u4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:rewind-backward-square-10-fill" /></template>
