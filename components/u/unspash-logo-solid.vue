<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cmtoz6mio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cmtoz6mio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:unspash-logo-solid" /></template>
