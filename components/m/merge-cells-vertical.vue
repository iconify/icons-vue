<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xkaguab1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xkaguab1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:merge-cells-vertical" /></template>
