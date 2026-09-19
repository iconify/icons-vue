<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jpfkku9mr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1408};
const content = `<path class="jpfkku9mr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:superscript" /></template>
