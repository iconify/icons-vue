<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pvoikd50e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pvoikd50e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:repeat-single-remix" /></template>
