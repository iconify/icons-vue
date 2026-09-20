<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fdxcr6b2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fdxcr6b2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:map-search-solid" /></template>
