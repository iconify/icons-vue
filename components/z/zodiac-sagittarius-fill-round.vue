<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iin4xh33f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iin4xh33f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zodiac-sagittarius-fill-round" /></template>
