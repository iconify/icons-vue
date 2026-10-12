<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jjo6adcjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jjo6adcjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:squares-intersect-filled" /></template>
