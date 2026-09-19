<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dvw6d3hwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dvw6d3hwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:moon-solid" /></template>
