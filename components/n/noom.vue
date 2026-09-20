<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jan0qac4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":41,"height":41};
const content = `<path class="jan0qac4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:noom" /></template>
