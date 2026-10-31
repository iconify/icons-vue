<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nlc_msnzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nlc_msnzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zodiac-leo-fill-round" /></template>
