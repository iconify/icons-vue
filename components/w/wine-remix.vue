<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s8wtxcbhp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s8wtxcbhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:wine-remix" /></template>
