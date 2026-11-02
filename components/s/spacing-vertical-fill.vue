<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hx698mupf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hx698mupf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:spacing-vertical-fill" /></template>
