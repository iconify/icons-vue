<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zddt3ibfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zddt3ibfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:trash-simple-bold" /></template>
