<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtw6cewip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="jtw6cewip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:remix" /></template>
