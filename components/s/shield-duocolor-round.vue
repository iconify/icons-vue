<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whr5k5f0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="whr5k5f0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shield-duocolor-round" /></template>
