<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cff26lznd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cff26lznd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:map-search-remix" /></template>
