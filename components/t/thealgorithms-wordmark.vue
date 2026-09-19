<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kjaj40bro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="kjaj40bro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:thealgorithms-wordmark" /></template>
