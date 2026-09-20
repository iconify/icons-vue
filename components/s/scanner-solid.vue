<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dgjy1tmpk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dgjy1tmpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:scanner-solid" /></template>
