<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/by3g3qbje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":429.02,"height":429.02,"left":116,"top":34.49};
const content = `<path class="by3g3qbje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:mastra-dark" /></template>
