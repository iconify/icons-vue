<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eivnb-q9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eivnb-q9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:wifi-none-duotone-round" /></template>
