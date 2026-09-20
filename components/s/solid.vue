<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u21r97bfn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u21r97bfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:solid" /></template>
