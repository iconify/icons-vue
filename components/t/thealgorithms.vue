<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-62rbbdn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="q-62rbbdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:thealgorithms" /></template>
