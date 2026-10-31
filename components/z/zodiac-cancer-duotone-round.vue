<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oging0-6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oging0-6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zodiac-cancer-duotone-round" /></template>
