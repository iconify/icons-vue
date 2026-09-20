<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1cmtz2bf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="g1cmtz2bf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:tune-adjust-volume-solid" /></template>
