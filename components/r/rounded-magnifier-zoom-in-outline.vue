<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g7g4d_bmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g7g4d_bmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rounded-magnifier-zoom-in-outline" /></template>
