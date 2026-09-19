<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aeehi_bkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aeehi_bkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:plug-type-l" /></template>
