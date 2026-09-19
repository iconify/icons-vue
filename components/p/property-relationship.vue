<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eg25gqbsq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="eg25gqbsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:property-relationship" /></template>
