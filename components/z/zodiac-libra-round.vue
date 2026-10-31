<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rdg1bxbnw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rdg1bxbnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zodiac-libra-round" /></template>
