<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxmsrw0ad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nxmsrw0ad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:ruler-solid" /></template>
