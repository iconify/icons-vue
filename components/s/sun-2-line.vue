<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7o8b1iri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u7o8b1iri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sun-2-line" /></template>
