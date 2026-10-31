<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/luemuubgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="luemuubgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:slider-2-round" /></template>
