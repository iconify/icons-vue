<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tktr2s5ge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":896,"height":1024};
const content = `<path class="tktr2s5ge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:pixelshield" /></template>
