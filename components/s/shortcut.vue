<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j25opi_1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j25opi_1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:shortcut" /></template>
