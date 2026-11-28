<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qmza4pb7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qmza4pb7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:radio-button" /></template>
