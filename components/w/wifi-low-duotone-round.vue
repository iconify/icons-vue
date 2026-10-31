<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fa_jubcgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fa_jubcgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:wifi-low-duotone-round" /></template>
