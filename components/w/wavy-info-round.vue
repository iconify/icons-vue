<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eqo-nvbqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eqo-nvbqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:wavy-info-round" /></template>
