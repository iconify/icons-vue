<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tfsxggyxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tfsxggyxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:medicine-search-4-bold" /></template>
