<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/te54cpbiz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="te54cpbiz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:pen-tool-solid" /></template>
