<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cgl11-bfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cgl11-bfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:snow-flake-solid" /></template>
