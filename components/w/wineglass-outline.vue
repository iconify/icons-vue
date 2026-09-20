<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/clc8j0pcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="clc8j0pcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:wineglass-outline" /></template>
