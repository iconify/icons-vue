<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/exb_8omph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="exb_8omph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:surveillance-camera-solid" /></template>
