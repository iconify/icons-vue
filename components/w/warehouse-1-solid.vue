<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x1pp6bkda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x1pp6bkda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:warehouse-1-solid" /></template>
