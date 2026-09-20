<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uwnd97ges.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uwnd97ges"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:wineglass-line" /></template>
