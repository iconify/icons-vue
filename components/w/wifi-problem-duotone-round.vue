<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rahubnbki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rahubnbki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:wifi-problem-duotone-round" /></template>
