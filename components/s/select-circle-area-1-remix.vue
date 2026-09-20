<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tupo72bxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tupo72bxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:select-circle-area-1-remix" /></template>
