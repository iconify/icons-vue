<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o3u6w5bbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o3u6w5bbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:party-popper-solid" /></template>
