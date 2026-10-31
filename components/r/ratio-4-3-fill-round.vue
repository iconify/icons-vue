<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n0brvyb2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n0brvyb2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:ratio-4-3-fill-round" /></template>
