<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/exs0fwbzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="exs0fwbzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:slider-vertical-1-round" /></template>
