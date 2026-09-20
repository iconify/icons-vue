<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2qh80col.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p2qh80col"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:unreal-engine-logo-block" /></template>
