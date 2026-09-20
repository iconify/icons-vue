<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g48g4ob_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g48g4ob_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:truck-arrow-right" /></template>
