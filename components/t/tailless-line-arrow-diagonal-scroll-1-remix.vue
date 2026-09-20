<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vfmva0bip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vfmva0bip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:tailless-line-arrow-diagonal-scroll-1-remix" /></template>
