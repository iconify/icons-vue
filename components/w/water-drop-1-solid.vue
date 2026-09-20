<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bf9ps8npn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bf9ps8npn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:water-drop-1-solid" /></template>
