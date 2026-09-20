<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ogv2_puag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ogv2_puag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp-color:warp-fish-flat" /></template>
