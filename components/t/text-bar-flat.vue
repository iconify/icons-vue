<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uvyox-byp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uvyox-byp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp-color:text-bar-flat" /></template>
