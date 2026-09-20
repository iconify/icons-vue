<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4x_hls7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="f4x_hls7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:pets-allowed-solid" /></template>
