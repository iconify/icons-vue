<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lm3nllbei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="lm3nllbei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:squarevoice" /></template>
