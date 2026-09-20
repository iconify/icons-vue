<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/swms12bvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="swms12bvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:wordpress-logo-1-solid" /></template>
