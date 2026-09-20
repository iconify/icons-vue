<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6uwribyz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x6uwribyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:play-list-8-solid" /></template>
