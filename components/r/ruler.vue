<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u9sohlbbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="u9sohlbbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:ruler" /></template>
