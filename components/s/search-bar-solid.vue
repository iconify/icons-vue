<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sglw8166b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sglw8166b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:search-bar-solid" /></template>
