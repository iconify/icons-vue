<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/st3avbbjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="st3avbbjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:novelai" /></template>
