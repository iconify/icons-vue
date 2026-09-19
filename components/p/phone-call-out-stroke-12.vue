<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4x29vb0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="g4x29vb0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:phone-call-out-stroke-12" /></template>
