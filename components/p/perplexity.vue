<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h82bhxfvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h82bhxfvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:perplexity" /></template>
