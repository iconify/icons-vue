<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i5c_1mbhw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i5c_1mbhw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:octagram-shape-remix" /></template>
