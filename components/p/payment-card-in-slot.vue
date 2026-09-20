<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jpt1l0w-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="jpt1l0w-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:payment-card-in-slot" /></template>
