<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w3945es9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w3945es9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mountain-duocolor-round" /></template>
