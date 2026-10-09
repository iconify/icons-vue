<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f9nf_fbqv.css';
import '../../css/r/rn7_tzbji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="f9nf_fbqv"/><path class="rn7_tzbji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:water-bottle-20-bold" /></template>
