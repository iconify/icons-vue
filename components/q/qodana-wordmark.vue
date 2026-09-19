<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/idk0c28mv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="idk0c28mv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:qodana-wordmark" /></template>
