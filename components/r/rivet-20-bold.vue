<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mixyt5cvw.css';
import '../../css/c/c-gfqebqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mixyt5cvw"/><path class="c-gfqebqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:rivet-20-bold" /></template>
