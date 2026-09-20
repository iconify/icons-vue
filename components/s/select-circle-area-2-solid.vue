<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h2bz9sbyh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h2bz9sbyh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:select-circle-area-2-solid" /></template>
