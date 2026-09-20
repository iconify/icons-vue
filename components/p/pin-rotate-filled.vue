<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxg2wgbpc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nxg2wgbpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:pin-rotate-filled" /></template>
