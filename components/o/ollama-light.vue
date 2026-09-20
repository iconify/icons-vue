<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f3yu5_g7l.css';
import '../../css/s/sq2gbtbfq.css';
import '../../css/f/fqm99lbwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":646,"height":854};
const content = `<path class="f3yu5_g7l"/><path class="sq2gbtbfq"/><path class="fqm99lbwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:ollama-light" /></template>
