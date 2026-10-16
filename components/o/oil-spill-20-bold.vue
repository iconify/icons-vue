<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ukc5chhna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ukc5chhna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:oil-spill-20-bold" /></template>
